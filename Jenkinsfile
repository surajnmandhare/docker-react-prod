pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
               'npm start test -- -- coverage'
            }
        }
    }
}
