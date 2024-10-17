pipeline{
    agent any
    stages{
        stage('NPM Install'){
            steps{
                bat 'npm install'
            }
        }

         stage('Execute test'){
            steps{
                bat 'npm test'
            }
        }
    }

}