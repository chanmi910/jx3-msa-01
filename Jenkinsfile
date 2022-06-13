pipeline {
  agent any
  stages {
    stage('Stage') {
      steps {
        checkout scm
        //tektonCreateRaw(inputType: 'FILE', input: 'tekton/argocd/pr-demo-argo.yaml')
        //tektonCreateRaw(inputType: 'URL', input: 'https://raw.githubusercontent.com/chanmi910/tekton-pipeline/master/jenkins/pr-dev-jenkins.yaml')
        tektonCreateRaw(inputType: 'URL', input: 'https://raw.githubusercontent.com/chanmi910/tekton-pipeline/master/jenkins/pr-test.yaml')
      }
    }
  }
}
