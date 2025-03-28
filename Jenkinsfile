pipeline {
    agent any

    tools {
        maven 'maven'  // Name of Maven installation in Jenkins
    }

    stages {
        stage("Build") {
            steps {
               sh 'mvn clean package'
            }
        }
        
        stage("Test") {
            steps {
                sh 'mvn test'
            }
        }
    }
}
