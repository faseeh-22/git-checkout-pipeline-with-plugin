pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Check out the code from the Git repository
                git branch: 'master', // Replace 'main' with the desired branch name
                    credentialsId: 'git-checkout-pipeline-with-plugin', // Optional if using credentials
                    url: 'https://github.com/faseeh-22/git-checkout-pipeline-with-plugin.git' // Replace with your Git repository URL
            }
        }
    }
}

