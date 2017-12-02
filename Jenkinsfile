pipeline {
  agent none
  stages {
    stage('di4') {
      parallel {
        stage('di4') {
          steps {
            sh 'echo "Ez pizy di4"'
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