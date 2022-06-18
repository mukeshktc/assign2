pipeline {
  agent 'any'
  stages {
    stage ('clone repo') {
      steps {
      echo 'cloning main branch of repository'
      git branch: 'main', url: 'https://github.com/mukeshktc/assign3.git'
      } 
    }  
  }
}
