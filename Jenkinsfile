#!groovy
node {
  stage('Build') {
    git 'https://github.com/jemichel2yahoo/hello.git'
    sh "./gradlew clean build"
  }
}
