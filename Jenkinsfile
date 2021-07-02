pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            app.inside {
               sh 'npm start test -- -- coverage'
            }
        }
    }
}
