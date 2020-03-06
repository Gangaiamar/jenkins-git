pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "single line shell shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
