pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from Git repository
                git 'https://github.com/Sushant-Mavenberg/jenkins.git'
            }
        }
        
        stage('Install Dependencies') {
            steps {
                // Install Python dependencies using pip
                echo 'Install Dependencies...'
            }
        }
        
        stage('Run Tests') {
            steps {
                // Placeholder message for running tests
                echo 'Running tests...'
            }
        }
        
        stage('Deploy') {
            // when {
            //     // Trigger deployment only on the master branch
            //     branch 'master'
            // }
            steps {
                // Placeholder message for deployment
                echo 'Deploying application...'
            }
        }
    }
    
    post {
        always {
            // Clean up or perform any post-build actions here
            echo 'Pipeline execution completed.'
        }
    }
}

