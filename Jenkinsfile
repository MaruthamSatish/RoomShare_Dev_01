pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/MaruthamSatish/RoomShare_Dev_01.git', branch: 'master', poll: true)
      }
    }
  }
}