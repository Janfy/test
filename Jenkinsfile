pipeline {
  agent {
    node {
      label 'ssh'
    }
    
  }
  stages {
    stage('Stage 1') {
      steps {
        parallel(
          "Stage 1": {
            echo 'Stage 1'
            
          },
          "Stage 2": {
            echo 'Stage 2'
            
          },
          "Stage 3": {
            echo 'Stage 3'
            
          }
        )
      }
    }
    stage('Stage 4') {
      steps {
        echo 'Stage 4'
      }
    }
  }
}