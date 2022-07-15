@Library("shared-library") _
pipeline {
  agent { label "linux" }
  stages {
    stage('example') {
      steps {
        //helloWorld() //this is used for when no string variablle is passed in the library
        helloWorld("Veronica", "Thursday") // used when a string variable is passed in the library
      }
    }

  }
}
