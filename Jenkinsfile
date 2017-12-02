pipeline {
  agent none
  stages {
    stage('di4') {
      parallel {
        stage('di4') {
          steps {
            echo 'fgfgfgfgfgfgfgfgfgfgfgfg'
          }
        }
        stage('klk') {
          steps {
            echo 'fgfgfgfgfgfg'
          }
        }
      }
    }
    stage('gg') {
      steps {
        git(url: 'https://github.com/ileusmaxim/HellowWorld.git', branch: 'master', poll: true)
      }
    }
  }
}