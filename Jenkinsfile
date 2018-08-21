//Declarative Pipeline

pipeline {

    agent any

    stages {

        stage('Build') {

            steps {
                
                git url: 'https://github.com/projeto3/DevOpsLab-HelloWorld.git'
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
