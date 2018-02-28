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

  stage('clean again') {
      steps {
          sh 'mvn clean'
           }

}
}
}
