node{
  stage('SCM Chekout'){
    git 'https://github.com/javahometech/my-app'
  }
  stage('Compile-Package'){
     // Get maven home path
    def mvnHome = tool name: tool name: 'maven3', type: 'maven'
    sh "${mvnHome}/bin/mvn/package"
  }

}
