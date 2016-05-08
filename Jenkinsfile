node {
   
   
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Get some code from a GitHub repository
   sh 'git clone https://github.com/JeanFrancoisMaes/DockerizeNodeJS .'
   
   stage 'Docker Composing'
     
     sh'docker-compose up -d'
     

}
