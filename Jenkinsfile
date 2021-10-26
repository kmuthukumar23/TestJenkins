pipeline { 
  
   agent any

   stages {
   
     stage('Install') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "Application Tested..."'
        }
      }

         stage("Deploy") { 
         steps { 
           sh 'echo "Application Deployed..."'
         }

     }
  
   	}

   }