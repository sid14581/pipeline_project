pipeline {
    //  script for runnin gthe pipeline using script
    //agent any
    // stages {
    //     stage('Test') {
    //         steps {
    //             sh './firstPipeline.sh'
    //         }
    //     }
    // }
    

    agent {
       docker { image 'node:16-alpine' }
    }
    stages {
      stage('Test') {
        steps {
          sh 'node --version'
        }
      }
    }

}