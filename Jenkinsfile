pipline {
    agent any 

    tools {
        maven 'Maven-3.9.9'
    }

    stages {
        stage("run frontend") {
            steps {
                echo 'executing npm ...'
                sh 'npm install axios'
            }
        }

        stage("run backend"{
            steps {
                echo 'executing maven ...'
                sh 'mvn --version'
            }
        })
    }

    
}