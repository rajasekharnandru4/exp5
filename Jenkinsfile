pipeline{
  agent any
  stages('compile'){
      steps{
      sh 'javac HelloWorld.java'
      }
      stage('Run'){
          steps{
              sh 'java HelloWorld'
              }
          }
      }
}
