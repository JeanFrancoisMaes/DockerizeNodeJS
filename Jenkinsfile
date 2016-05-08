node {
   
   stage 'Cleaning up workspace'
   sh 'rm -rf *'
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Get some code from a GitHub repository
   sh 'git clone https://github.com/JeanFrancoisMaes/DockerizeNodeJS .'
   sh 'mv master/* .'
   

}
