node ('master') {
  //directive 1
  def myHome

  //stage block 1
  stage('Perparation') {
    //step1
    git 'https://github.com/sageldy/fcdocker-whale.git'

    //directive 2
    myHome = tool 'workspaces'
  }
  stage('Build'){
    //step 2
    sh "cat '${myHome}/dockerfile'"
  }

  stage('Result'){
    sh "echo '하하하 hellow world !!'"
  }
}
