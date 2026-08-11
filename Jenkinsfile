pipeline{
  agent any
  stages('complie'){
      steps{
      sh'javac HelloWorld.java'
      }
      stage('Run'){
          steps{
              sh 'java HelloWorld'
              }
          }
      }
}
