pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
             sh 'ansible --version'
             sh 'ansible-playbook beats.yml'
      }
    }
  }
}
