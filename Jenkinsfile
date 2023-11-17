pipeline {
  agent any
  stages {
    stage('main') {
      when {
        branch 'main'
      }
      steps {
        echo 'hello main..........'
      }
    }
    stage('develop') {
      when {
        branch 'branch-1'
      }
      steps {
        echo 'hello branch-1.......'
      }
    }
  }
}
