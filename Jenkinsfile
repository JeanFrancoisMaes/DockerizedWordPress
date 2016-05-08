node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Get some code from a GitHub repository
      git url: 'https://github.com/JeanFrancoisMaes/DockerizedWordPress'
   
   stage 'Docker Composing'
     
     sh'docker-compose up -d'
     
   stage 'cleaning workspace'
   sh 'rm -rf *'
}
