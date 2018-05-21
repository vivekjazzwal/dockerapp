pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git(url: 'git@github.com:vivekjazzwal/dockerapp.git', branch: 'v0.8', changelog: true)
      }
    }
  }
}