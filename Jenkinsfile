pipeline {
  agent any
  stages {
    stage("Change dir") {
      steps {
        sh 'cd demo-test'
      }
    }
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
