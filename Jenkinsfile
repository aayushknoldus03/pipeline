node{
  stage("git repo"){
     git branch: 'main', url: 'https://github.com/aayushknoldus03/pipeline.git'
  }
  stage("java"){
    sh "javac Hello1.java"
    sh "java Hello1"
  }
}
