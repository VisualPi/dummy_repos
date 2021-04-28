stages {
  stage('Clone & Checkout') {
    steps {
        echo "====++++Cloning dummy_repos++++===="
        git branch: 'main', credentialsId: 'ViPiCredentials', url: 'https://github.com/VisualPi/dummy_repos.git'
      // One or more steps need to be included within the steps block.
    }
  }

  stage('Build') {
    steps {
        echo "====++++Building project++++===="
      // One or more steps need to be included within the steps block.
    }
  }

  stage('Unit Test') {
    steps {
        echo "====++++Run unit tests++++===="
      // One or more steps need to be included within the steps block.
    }
  }

}
