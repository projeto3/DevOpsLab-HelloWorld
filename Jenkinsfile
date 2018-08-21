//Declarative Pipeline

pipeline {

    agent any

    stages {

        stage('Build') {

            steps {
                
                git url: 'https://github.com/projeto3/DevOpsLab-HelloWorld.git'
                sh 'pip install -r requirements.txt'
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
