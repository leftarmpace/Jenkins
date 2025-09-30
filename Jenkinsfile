pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "Hello for first Jenkinsfile"
            }

        }
    }
    post{
        success{
            echo "Pipeline is successfull"

        }
        failure{
            echo "Not done yet"
        }
    }
}