pipeline {
    agent any
    stages {
        stage('build') { 
            steps {
                sh 'bash ./build.sh' 
                sh 'bash ls -la .' 
            }
        }
        stage('functional-test') { 
            steps {
                sh 'bash ./build.sh' 
            }
        }
        stage('test') { 
            steps {
                sh 'bash ls -la .' 
            }
        }
    }
}
