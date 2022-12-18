pipeline {
    agent any

    stages {
        stage('click') {
            steps {
                sh 'click.py'
            }
        }
                stage('Welcome') {
            steps {
                sh 'welcome.py'
            }
        }
    }
}
