node {
  stage('Build') {
    echo 'building'
    // Simulate success by setting the result explicitly
    currentBuild.result = 'SUCCESS'
  }
  
  stage('Test') {
    echo 'testing'
  }
  
  script {
    // Check the build result
    if (currentBuild.result == 'SUCCESS') {
      echo 'looks good'
    } else {
      echo 'failed'
    }
  }
}
