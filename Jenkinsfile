pipeline {
    agent any

    stages{
        stage("Build"){
            steps{
                bat 'printf "123"'
              
            }
        }
    }
    post{
        always{
            cleanWs()
        }
    }
}
