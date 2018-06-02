pipeline {
	agent any

    stages {
    
    stage('Compile Stage'){
       steps{
          withMaven(maven : 'M2_Home'){
          
          sh 'mvn clean compile'
          
          }
       }
    
    }
    
    
    }


}