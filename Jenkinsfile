pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
             sh 'ansible-playbook elastic.yml'
      }
    }
  }
}
