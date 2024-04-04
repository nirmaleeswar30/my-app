node{
  stage('SCM Checkout'){
    git 'https://github.com/nirmaleeswar30/my-app.git'
  }
  stage('Compile-Package'){
    // Get maven hoime path
    def mvnHome = tool name: 'maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn package
        }
        }
