pipeline
{
    agent any
    stages
    {
        stage('Checkout')
        {
            steps
            {
                // Checkout the code from the repository
               git url: 'https://github.com/Manasa-devops/nikit-jenkins.git'
            }
        }
        stage('Build')
        {
            steps 
            {
               echo 'Build app'
               sh 'deliver.sh' 
            }
        }

        stage('Deploy')
        {
            steps
            {
               echo 'Deploy app'
            }
        }    
    }                                                                                                                                                                 
}
