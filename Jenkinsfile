pipeline {
    agent any

    environment {
      ENV_URL = "pipeline.google.com"
    }
    stages {

        stage('Zero') {
            steps {

                sh '''echo vai
                echo love
                echo 'Zero'
                echo ENV_URL = ${ENV_URL}'''
            }
        }
        stage('One') {
         environment {
              ENV_URL = "stage.google.com"
            }
            steps {
               echo 'One'
               sh 'echo ENV_URL = ${ENV_URL}'
            }
         }
    }
}