pipeline { 
   agent any
   tools{
     nodejs 'nodejs'
   }
   stages {
     stage('scm') { 
        steps { 
           checkout scm
        }
     }
     stage('npm') {    
       steps{
         sh 'npm install'
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
