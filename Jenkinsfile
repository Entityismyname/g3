pipeline{
  agent{label "linux"}
  options {
    buildDiscarder logRotator(artiFactDaysToKeepStr: '',artifactNumToKeeStr:, daysToKeepStr: '', numToKeepStr: '5'}
    disableConcurrentBuild{}
}
  stages {
    stage('Hello'){
      steps {
        echo "hello"
      }
    }
  }
                              }
