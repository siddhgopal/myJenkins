pipeline{
    agent{
        label "node"
    }
    stages{
        stage("Git pull source code "){
            steps{
                git branch: 'master',url: ''
            }
        } 
        stage('compile source'){
            steps {
                bat ``` cd /D D:\\Learning\\localgitrepo
                npm install ```
            }
        } 
        stage('hello'){
            steps{
                echo 'Hellow world'
            }
        }     
    }
}   
