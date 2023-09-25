
 pipeline{
   agent{
        node { label 'workstation'}
        }
    stages {

      stage('Build') {
       steps{
         sh 'npm install'
       }
    }
      stage ('unit tests') {
        steps {
         echo 'unit tests'
        }
      }
      stage ('Code Analysis') {
         steps {
            echo 'Code Analysis'
         }
      }

      stage ('Security Scans') {
         steps {
            echo 'Security Scans'
          }
      }

      stage ('Publish a Artifact') {
        steps {
            echo 'Publish a Artifact'
        }
     }

  }
 }