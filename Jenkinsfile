pipeline {
    agent any

    options {
      timeout(time: 1, unit: 'HOURS') 
    } 


    stages {
        stage("Install Dependencies") {
            steps {
                sh "npm install"
            }
        }

        stage ("Unit Testing") {
            steps {
                echo "Done by Developers"
            }
        }
    }
}