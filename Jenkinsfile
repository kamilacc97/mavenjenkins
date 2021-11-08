pipeline {
    agent any

    stages{
        stage("Build"){
            steps{
                echo "mvn -version"
                echo "mvn clean install"
            }
        }
    }
    post{
        always{
            cleanWs()
        }
    }
}
