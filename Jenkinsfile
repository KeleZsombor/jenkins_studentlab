pipeline {
    agent any
    stages {
        stage('first') {
            steps {
                sh 'ping google.com -c 5'                
            }
        }
        stage('second') {
            steps {
                sh '/var/lib/jenkins/workspace/script/sc.sh'                
            }
        }
        stage('third') {
            steps {
                sh 'curl https://192.168.56.200'                
            }
        }
    }
}
