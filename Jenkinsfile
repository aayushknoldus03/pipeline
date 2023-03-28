node{
  stage("git repo"){
     git branch: 'main', url: 'https://github.com/aayushknoldus03/jenkinsdemoproject'
  stage("java"){
    sh "javac Hello.java"
    sh "java Hello"
  }
}
