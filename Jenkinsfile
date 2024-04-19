pipeline {
  agent any
  stages {
    stage("Change dir") {
      steps {
        cd demo-test
      }
    }
    stage("PNPM Pose") {
      steps {
        pnpm install 
      }
    }
    stage("Running Server") {
      steps {
        pnpm run dev
      }
    }
  }
}
