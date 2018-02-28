pipeline {
  agent any

  stages {
   stage('build') {
      steps {
          sh 'mvn install'
           }
}
     stage('install') {
      steps {
          sh 'mvn install'
            }
}

  stage('docker step') {
      steps {
          sh 'sudo docker pull centos'
           }

}
}
}
