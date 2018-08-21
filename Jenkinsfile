//Declarative Pipeline

pipeline {

    agent any

    stages {

        stage('Build') {

            steps {
                
                git url: 'https://github.com/projeto3/DevOpsLab-HelloWorld.git'
                sh 'sudo yum install python-3.6.3'
                echo 'Building..'

            }

        }

        stage('Test') {

            steps {
                
                
                echo 'Testing..'

            }

        }

        stage('Deploy') {

            steps {

                echo 'Deploying....'

            }

        }

    }

}
