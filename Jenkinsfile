pipeline {
  agent { label 'codebuilder' }

  stages {
    stage('Build with Codebuild') {
      steps {
        sh 'docker build -t test1:1.0 .'
      }
    }
  }  
}
//https://github.com/dimmel82/simple-docker.git