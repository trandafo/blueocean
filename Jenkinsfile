pipeline {
  agent any
  stages {
    stage('cleanup_workspace') {
      steps {
        deleteDir()
      }
    }
    stage('') {
      steps {
        git(url: 'git@github.com:trandafo/blueocean.git', branch: 'develop')
      }
    }
  }
}