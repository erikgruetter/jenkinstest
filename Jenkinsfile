pipeline 
{

    agent any

    stages
    {

            stage("build") 
            {
                steps
                {
                powershell 'Write-Output "Hello, World!"
                    write-host $env:test'
                }
            }

    }
}
