//Jenkinsfile (myPipe)
pipeline {
    agent any

    stages {
         stage('PreBuild') {
            steps {
                println 'Pre-Building..'
            }
        }
        stage('Build') {
            steps {
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
