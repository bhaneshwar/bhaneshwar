pipeline {
   agent any
   stages {
       stage('Build QA Code') {
           steps {
               sh """
               echo "Building Artifact from Develop Branch"
               """
           }
       }
      
       stage('Code QA Test') {
           steps {
               sh """
               java Helloworld
               """
           }
       }
      stage('Deploy QA Code') {
          steps {
               sh """
               echo "Deploying Code from Develop Branch"
               """
          }
      }
   }
}
