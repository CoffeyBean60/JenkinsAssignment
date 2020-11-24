pipeline {
    agent any
   
    stages {
      
        stage ('Authentication Stage') {
            steps {
                input("Do you want to proceed?")
            }
        }
        
        stage ('Email') {
            steps {
                emailext body: 'Now', subject: 'Test', to: 'rafikarim1414@gmail.com'
            }
        }
       
        
    }
}
