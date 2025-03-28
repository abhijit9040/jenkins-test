pipeline {
    agent any

    tools {
        maven 'maven'  // Name of Maven installation in Jenkins
    }

    stages {
        stage("Build") {
            steps {
                bat 'mvn clean package'
            }
        }
        
        stage("Test") {
            steps {
                bat 'mvn test'
            }
        }
    }
}
