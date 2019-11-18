pipeline {
    agent any
    stages {
        stage('first') {
            steps {
                sh 'ping google.com'                
            }
        }
        stage('second') {
            steps {
                sh '/var/lib/jenkins/workspace/script/sc.sh'                
            }
        }
        stage('third') {
            steps {
                sh 'curl 192.168.56.200'                
            }
        }
    }
}
