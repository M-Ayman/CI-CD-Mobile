node{
  stage('Checkout') {
    git url: 'https://github.com/WahdanZ/Hellojenkins'

  }

  stage('Build') {
    sh './gradlew assembleDubg'

  }
}
