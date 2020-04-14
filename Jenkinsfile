node{
   stage('SCM Checkout'){
     git 'https://github.com/GattuBhavani/gitclone'
   }
   stage('compile-package'){
      // Get maven home path
      def mvnHome = tool name: 'maven-3', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
   
}
