  
pipeline{

agent any;
    tools{
        maven 'Maven'
    }
    
    stages{
    	stage('get build from Git'){
	    steps{
	    git branch: 'master', credentialsId: 'GIT', url: 'https://github.com/Adinarayana-gethub/php-helloworld.git'
            }
           }
