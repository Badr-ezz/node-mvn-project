pipeline {
    agent any 

    tools {
        maven 'Maven-3.9.9'
    }
    
    stages {
        stage("run frontend") {
            steps {
                echo 'executing npm ...'
               nodejs('Node-23.11.0') {
                    sh 'node --version'
              }
            }
        }

        stage("run backend") {
            steps {
                echo 'executing maven ...'
                sh 'mvn --version'

            }
        }
    }

    
}
