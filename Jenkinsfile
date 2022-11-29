node{
  stage('SCM Chekout'){
    git 'https://github.com/Wesley-oss2/my-app'
  }
  stage('Compile-Package'){
     // Get maven home path
    def mvnHome = tool name: 'maven3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }

}
