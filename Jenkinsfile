pipeline {
    agent any
stages {

           
         stage('Build-Step') {
             steps {
                     echo 'Build Step '
             }
         }
     

        stage('Change-Step') {
              steps {
                   echo 'Change Step'
                   snDevOpsChange()
              }
        }
    
    
    stage('Post-Change-Step') {
              steps {
                   echo 'Post-Change Step'
                   
              }
        }
    
}

   
}
