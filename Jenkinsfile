pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "secondary_branch"'
                sh '''
                    echo "Multiline shell steps works too --- 4 "
                    ls -lah
                '''
            }
        }
    }
}
