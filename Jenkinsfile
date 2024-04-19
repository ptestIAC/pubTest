pipeline {
  agent any
  tools {nodejs "nodejs"}
  stages {
    stage("Change dir") {
      steps {
        sh 'cd demo-test'
      }
    }
    stage("PNPM Pose") {
      steps {
        sh 'pnpm install'
      }
    }
    stage("Running Server") {
      steps {
        sh 'pnpm run dev'
      }
    }
  }
}
