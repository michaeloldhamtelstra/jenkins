def isDevEnv = ENVIRONMENT.equals("dev")
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pwd'
                sh 'printenv'
            }
        }
    }
}
