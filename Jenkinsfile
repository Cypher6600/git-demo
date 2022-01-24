pipeline { 
    agent any 
    
    stages {
        stage('Uploading to S3') { 
            steps { 
                sh 'aws s3 cp --profile PowerUserAccess-529396670287 . s3://bill-bucket-66 --recursive --acl public-read' 
            }
        }
    }
}
