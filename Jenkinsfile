node('nodejs') {
  stage('Checkout') {
     git branch: 'main', url: 'https://github.com/pin2poo/do400-pipelines-control
  stage('Backend Tests') {
     sh 'node ./backend/test.js'
}
  stage('Frontedn Tests') {
     sh 'node ./frontend/test.js'
}

}
}
