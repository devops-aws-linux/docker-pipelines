pipeline{
    agent{
        docker {
            image 'node:16-alpine'
        }
    }
    stages{
        stage('version'){
            steps{
                sh 'node --version'
            }
        }
    }
}