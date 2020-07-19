pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "its a build stage" 
            }
        }
        stage('Test') { 
            steps {
                echo "its a test stage"
            }
        }
        stage('Deploy') { 
            steps {
                echo "its a deploy stage"
            }
        stage('email build') { 
            steps {
                mail bcc: '', body: 'from jenkins', cc: '', from: '', replyTo: '', subject: 'sample', to: 'bikram6singha@gmail.com'
            } 
        }
    }
}
