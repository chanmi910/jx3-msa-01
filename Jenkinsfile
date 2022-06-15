pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        checkout scm
        tektonCreateRaw(inputType: 'URL', input: 'https://raw.githubusercontent.com/chanmi910/tekton-pipeline/master/pipelinerun/pr-app.yaml')
      }
    }
  }
}
