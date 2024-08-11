pipeline {
    agent { 
        node {
            label 'docker-agent-alpine'
            }
      }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                echo 'doing build stuff..'
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo 'doing testing stuff..'
                '''
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
