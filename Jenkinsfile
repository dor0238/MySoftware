pipeline {
    agent any

    stages {
        stage('click') {
            steps {
                sh 'python click.py'
            }
        }
                stage('Welcome') {
            steps {
                sh 'python welcome.py'
            }
        }
    }
}
