#!groovy
node {
  git 'https://github.com/jemichel2yahoo/hello.git'
  def gradleHome = tool 'GRADLE'
  sh "${gradleHome}/bin/gradle clean build"
}
