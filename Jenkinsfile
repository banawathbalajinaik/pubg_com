pipeline {
    agent any
    stages {
        stage ("git_clone") {
            steps {
                sh '''
                echo "this is banawath balajinaik %date% : %time%"
                git clone 'https://github.com/banawathbalajinaik/maven_whatsapp.com.git'
                '''
            }
        }
    }
}
