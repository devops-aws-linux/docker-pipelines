pipeline{
    agent{
        docker {
            image 'node:16-alpine'
            /*args '-v /var/run/docker.sock:/var/run/docker.sock'*/
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