pipeline {  
   agent any
   tools{
    nodejs 'nodejs'
   }

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           git 'https://github.com/SREEKANTH-NARAHARI/test-nodejs-app.git'
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
