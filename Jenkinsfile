node{
   stage('SCM Checkout'){
     git 'https://github.com/GattuBhavani/gitclone'
   }
   stage('compile-package'){
     sh 'mvn pack'
   }
   
}
