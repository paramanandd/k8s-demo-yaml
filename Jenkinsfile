node {
   def mvnHome
   stage('Preparation') { // for display purposes
      cat deployment.yaml
   }
   stage('Build') {
      // Run the maven build
      echo "in stage build"
   }
   stage('Results') {
      cat service.yaml
   }
}
