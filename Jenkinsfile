node{
  stage('SCM Checkout'){
 
  
  git 'https://github.com/Bhavyanth/mavenrepo'
  }
  stage('Compile-Package'){
   def mvnHome = tool name: '', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
  }
}
