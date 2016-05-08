node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Get some code from a GitHub repository
   git url: 'https://github.com/JeanFrancoisMaes/DockerizedWordPress'

stage 'docker compose'

sh 'docker-compose up'

stage 'cleaning workspace'
sh 'rm -rf *'
