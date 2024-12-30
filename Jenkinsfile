pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */

   agent any 

    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building project...'
                    // TODO: Run the Gradle build command
                    sh './gradlew assemble'  
                }
            }
        }
    
    stage('Test') {
            steps {
                script {
                    echo 'Running tests...'
                    // TODO: Run the Gradle test command
                    sh './gradlew test'  
                }
            }
        }
      }
}
