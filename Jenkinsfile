pipeline {
    agent any

    // tools { nodejs "node"}

    stages {
        stage("Build") {
            steps {
                script {
                echo "Hala from building !!"
                bat "npm install"
                }
            }
        }
         stage("Test") {
            steps {
                script {
                echo "Here is the Testing"
                }
            }
        }
         stage("Deploy") {
            steps {
                script {
                bat "npm start"
                }
            }
        }
    }
}