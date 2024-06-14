pipeline {

    agent {label 'maven_build_server'}
    stages {
        stage('Maven Build stage') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
