pipeline {

    agent any
    
    stages {
         stage('dependencies') {
          steps {
              bat 'npm install'
            }
          }
          stage('build') {
          steps {
              bat 'npm run build'
            }
          }
        
      
    }
}
