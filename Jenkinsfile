pipeline {
   agent any
   tools {
     maven 'maven3'
   }
  stages{
    stage('checkout the project') {
      steps {
        
        git branch: 'main', url: 'https://github.com/sandeepprasad0707/Java-Maven-Pipline.git'
      }
    }
    stage('Build'){
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }      
} 
 
 
 
 
 
