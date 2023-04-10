pipeline {
  agent any
  stages {
    stage('git pull') {
      steps {
        git(url: 'https://github.com/jc2000/tilemill.git', branch: 'tile_loader ')
      }
    }

    stage('Run') {
      steps {
        sh 'sh start.sh'
      }
    }

  }
}