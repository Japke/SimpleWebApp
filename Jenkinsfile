node {
   stage('Preparation') {
      git 'https://github.com/Japke/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}