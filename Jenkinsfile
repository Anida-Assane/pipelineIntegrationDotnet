pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'dotnet build pipelineIntegration.sln'
        bat 'dotnet build pipelineIntegration.sln'
      }
    }

  }
}