pipeline {
    agent any

    environment {
      ENV_URL = "pipeline.google.com"
    }
    stages {

        stage('Zero') {
            steps {
                echo 'Zero'
                sh '''echo vai
                echo love'''
                echo ENV_URL = ${ENV_URL}
            }
        }
        stage('One') {
            steps {
               echo 'One'
               sh 'echo ENV_URL = ${ENV_URL}'
            }
         }
    }
}