pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                    pwd
                '''
                sh '''
                users
                uname -a
                sh ./hello_test.sh
                '''
            }
        }
    }
}
