pipeline {
  agent {
    ubuntu-test
  }
  stages {
    stage ('clone repo') {
      steps {
      echo 'cloning test branch of repository'
      git branch: 'test', url: 'https://github.com/mukeshktc/assign3.git'
      } 
    }  
  }
}
