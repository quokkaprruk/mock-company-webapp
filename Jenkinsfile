pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building project...'
                    // Run the Gradle build command
                    sh './gradlew assemble'
                }
            }
        }
    
        stage('Test') {
            steps {
                script {
                    echo 'Running tests...'
                    // Run the Gradle test command
                    sh './gradlew test'
                }
            }
        }
    }
 }

