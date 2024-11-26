pipeline {  
   agent any
   tools{
    nodejs 'nodejs'
   }

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           git credentialsId: '7df1c285-641c-4981-bd73-dda219b9e700', url: 'https://github.com/SREEKANTH-NARAHARI/test-nodejs-app.git'
        }
     }
     
     stage('Test') {
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
