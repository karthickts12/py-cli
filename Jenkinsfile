pipeline {
    agent any
stages {
stage('Checkout') {
            steps {
                git branch: 'main',                         // Or change to correct branch if not 'main'
                    credentialsId: 'a0772e31-ec14-41f4-98f7-e3b5954b0996',   // Replace with your actual Jenkins credentials ID
                    url: 'https://github.com/karthickts12/py-cli.git'
            }
        }
}
}
