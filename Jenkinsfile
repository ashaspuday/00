pipeline {
  environment {

    imagename = "{ashaspuday}/mynginxapp"  

    registryCredential = 'ashaspuday'

    dockerImage = ''

    }
    
    agent any

 

    stages {

         stages {

        stage('Git Clone') {

            steps {

                git([url: 'https://github.com/ashaspuday/Jenkinsforkdemo1.git', branch: 'master', credentialsId: 'ashaspuday'])

            }

        }
         }
    }
 

 
