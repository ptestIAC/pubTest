pipeline {
  agent any
  stages {
    stage("PNPM Pose") {
      steps {
        sh 'npm install'
      }
    }
    stage("Running Server") {
      steps {
        sh 'npm run dev'
      }
    }
  }
}
