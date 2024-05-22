pipeline {
    agent {label "PRD-WIN12"}
    stages {
        stage('Build') {
            steps {
                echo "Building ${env.BRANCH_NAME}"
            }
        }
        stage('Test') {
            steps {
                echo "Testing ${env.BRANCH_NAME}"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying ${env.BRANCH_NAME}"
            }
        }
    }
}
