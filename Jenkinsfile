pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }

        stage('Run Server') {
            steps {
                bat 'java -jar target\\jenkins-maven-demo-1.0.jar'
            }
        }

    }
}
