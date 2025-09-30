 pipeline { 
    agent any 
    environment { 
        MOVIE_NAME = 'CloudFolks Production' 
    } 
    stages { 
        stage('Build') { 
            steps { 
                echo "Shooting the scene for ${MOVIE_NAME}..." 
            } 
        } 
    } 
    post { 
        success { 
            echo 'Movie completed successfully!' 
        } 
        failure { 
            echo 'Reshoot required — something failed!'
        }
    }
}