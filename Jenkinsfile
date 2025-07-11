pipeline{
    agent any
        stages{
            stage('hostname'){
                steps{
                    sh 'hostname'

                }
            }
            stage('memory usage'){
                steps{
                    sh 'free -h'
                }
            }
            stage('disk usege'){
                steps{
                    sh 'df-kh'
                }
            }

           stage('ip address')
           {
            steps{
                sh 'hostname -I'
            }
           }
           stage('cpu details'){
            steps{
                sh 'lscpu'
            }
           }
        }

    
}
