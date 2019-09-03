pipeline {
  agent {
    node {
      label 'pipeline-test'
    }

  }
  stages {
    stage('build') {
      steps {
        sh '''date ;
echo "build completed"'''
        echo 'building'
      }
    }
    stage('test') {
      steps {
        sh '''date ;
echo "Test complete"'''
        echo 'Testing'
      }
    }
    stage('Deploy') {
      steps {
        sh '''date ;
echo "Deploy complete"'''
        echo 'Deploying'
      }
    }
  }
}