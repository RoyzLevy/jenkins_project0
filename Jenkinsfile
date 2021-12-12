pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
				echo 'First, get the code from SCM'
				git 'https://github.com/RoyzLevy/jenkins_project0'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing...'
            }
        }
    }
}
