pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
             sh 'ansible --version'
             sh 'ansible-galaxy --version'
             sh 'ansible-playbook --version'
             sh 'ansible-playbook beats.yml'
      }
    }
  }
}
