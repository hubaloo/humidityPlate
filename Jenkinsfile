pipeline {
  agent any
  environment {
    GIT_COMMITTER_NAME = "hosszubalazs"
    GIT_COMMITTER_EMAIL = "hbal0028@gmail.com"
    ENV_VAL_POC = "ENV_VAl wokrs! Huzzah!"
  }
  stages {
    stage("Test Unit") {
      steps {
        sh 'python3 -m unittest discover -s test/ -p *test.py'
      }
    }
  }
}