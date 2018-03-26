pipeline {
  agent any
  stages {
    stage('') {
      steps {
        echo 'Starting build'
        sh './gradlew build'
        mail(subject: 'Build A', body: 'Finished', to: 'aran.kilroy@zenjob.com')
      }
    }
  }
}