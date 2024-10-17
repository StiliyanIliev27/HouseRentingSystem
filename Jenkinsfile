pipeline{
    agent any
    stages{
        stage("Restore"){
            steps{
                bat "dotnet restore"
            }
        }
        stage("Build"){
            steps{
                bat "dotnet build"
            }
        }
        stage("Execute tests"){
            steps{
                bat "dotnet test"
            }
        }
    }
}
