pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        git(poll: true, branch: 'master', url: 'https://github.com/ileusmaxim/HellowWorld.git')
      }
    }
  }
}