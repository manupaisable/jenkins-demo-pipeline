pipeline {
    agent any
    stages {
        stage('build') { 
            steps {
                sh 'bash ./build.sh' 
                sh 'bash -c ls -la .' 
            }
        }
        stage('functional-test') { 
            steps {
                sh 'bash ./build.sh' 
            }
        }
        stage('deploy') { 
            steps {
                sh 'bash -c ls -la .' 
            }
        }
    }
}
