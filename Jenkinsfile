node{
  stage('Checkout') {
    git url: 'https://github.com/WahdanZ/Hellojenkins'

  }

  stage('Build') {
    sh './gradlew clean assembleDubg'
    archiveArtifacts 'app/build/outputs/apk/debug/app-debug.apk'

  }
}
