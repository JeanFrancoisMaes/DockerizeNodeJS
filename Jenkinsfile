node {

      stage 'cleaning workspace'
   sh 'rm -rf *'
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Get some code from a GitHub repository
    sh 'cd ..'
    sh'git init'
    sh'git remote add origin https://www.github.com/JeanFrancoisMaes/DockerizeNodeJS'
    sh'git fetch origin'
    sh'git checkout -b master --track origin/master'
 

     

}
