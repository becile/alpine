pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        echo 'aa'
      }
    }
    stage('step2') {
      steps {
        echo 'bbb'
        input(message: 'sss', id: 'sssid', ok: 'sssok', submitter: 'subm', submitterParameter: 'submp')
      }
    }
  }
}