pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'ssh 10.10.101.131 "cd /var/www/html/; git pull"'
            }
        }
    }
}
