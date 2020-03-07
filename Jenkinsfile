pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World There"'
                sh '''
                    echo "Multiline shell steps works too again"
                    ls -lah
                '''
            }
        }
    }
}
