pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
             sh 'ansible-playbook beats.yml'
      }
    }
  }
}
