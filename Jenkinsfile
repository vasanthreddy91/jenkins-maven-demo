
pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

        stage('Run Server') {
            steps {
                sh 'java -jar target/jenkins-maven-demo-1.0.jar'
            }
        }

    }
}
