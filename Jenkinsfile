pipeline {
  agent { label 'codebuilder' }

  stages {
    stage('Build with Codebuild') {
      steps {
        sh 'docker build -t test1:1.0'
      }
    }
  }  
}
