node{
  stage('SCM Chekout'){
    git 'https://github.com/javahometech/my-app'
  }
  stage('Compile-Package'){
        sh 'mvn package'
  }

}
