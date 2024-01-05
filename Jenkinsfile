pipeline {
  agent any
  stages {
    stage('message') {
      steps {
        echo 'hello'
      }
    }

    stage('build') {
      steps {
        bat 'dotnet build pipelineIntegration.sln'
      }
    }

  }
}