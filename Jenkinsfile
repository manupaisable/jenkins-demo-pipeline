pipeline {
    agent any
    stages {
        stage('build') { 
            steps {
                sh 'bash ./build.sh' 
            }
        }
        stage('functional-test') { 
            steps {
                sh 'bash ./build.sh' 
            }
        }
        stage('deploy') { 
            steps {
                sh 'bash ./build.sh' 
            }
        }
    }
}
