pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
        stage('validate') {
            steps {
                bat 'mvn validate'
            }
        }
        stage('build') {
            steps {
                bat 'mvn package'
            }
        }
    }
}
