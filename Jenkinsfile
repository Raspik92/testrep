pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Raspik92/testrep.git'
            }
        }

        stage('Run script') {
            steps {
                sh 'chmod +x app.sh'
                sh './app.sh'
            }
        }
    }
}i
