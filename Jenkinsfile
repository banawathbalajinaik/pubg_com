pipeline {
    agent any
    stages {
        stage ("git_clone") {
            steps {
                bat '''
                echo "this is banawath balajinaik %date% : %time%"
                git clone 'https://github.com/banawathbalajinaik/pubg_com.git'
                '''
            }
        }
    }
}
