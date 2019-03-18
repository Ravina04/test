node{
  stage('SCM ckeckout'){
   
    git 'https://github.com/Ravina04/test'
  }
  stage('Compile-Package){
     def mvnHome  =   tool name: 'maven', type: 'maven'
    
        sh "${mvnHome}/bin/mvn package"
  }
}
