pipeline{
    agent any
    stages{
        stage("Build Project"){
            steps{
                bat 'dotnet build SeleniumBasicExercise.sln'
            }
        }
        stage("Execute Tests for TestProject1"){
            steps{
                bat 'dotnet test TestProject1/TestProject1.csproj'
            }
        }
        stage("Execute Tests for TestProject2"){
            steps{
                bat 'dotnet test TestProject2/TestProject2.csproj'
            }
        }
        stage("Execute Tests for TestProject3"){
            steps{
                bat 'dotnet test TestProject3/TestProject3.csproj'
            }
        }
    }
}