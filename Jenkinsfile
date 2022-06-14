pipeline {
  agent any
  stages {
    stage('Stage') {
      steps {
        checkout scm
        tektonCreateRaw(inputType: 'URL', input: 'https://raw.githubusercontent.com/chanmi910/tekton-pipeline/master/jenkins/pr-p-dev-jenkins.yaml')
      }
    }
  }
}
