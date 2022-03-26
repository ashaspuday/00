pipeline {
  environment {

    imagename = "{ashaspuday}/mynginxapp"  

    registryCredential = 'wo7and-dockerhub'

    dockerImage = ''

    }
    
    agent any

 

    stages {

        s stages {

        stage('Git Clone') {

            steps {

                git([url: 'https://github.com/ashaspuday/Jenkinsforkdemo1.git', branch: 'master', credentialsId: 'ashaspuday'])

            }

        }

 

 
