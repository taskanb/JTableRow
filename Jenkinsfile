pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo 'Building...'
          bat './src/JTableRow.java'
		  echo 'Build Ends!'
   
        }
   }
   stage('Test') {
     steps {
        echo 'Testing...'
     }
   }
   stage('Deploy') {
     steps {
       echo 'Deploying...'
     }
   }
  }
}
