pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "hello from the first pipeline"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
