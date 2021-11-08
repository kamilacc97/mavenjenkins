pipeline {
    agent any

    stages{
        stage("Build"){
            steps{
                sh "printf '123'"
              
            }
        }
    }
    post{
        always{
            cleanWs()
        }
    }
}
