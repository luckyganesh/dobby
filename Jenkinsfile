node {
  stage('SCM Checkout') {
    git(url: 'https://github.com/luckyganesh/dobby')
  }

  stage('run make') {
    sh 'make compile'
  }
}
