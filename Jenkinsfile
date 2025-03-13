pipeline{
    agent any
    parameters{
        booleanParam(name: "enable_service", description: "Enable Service", defaultValue: false)
        string(name: "environment", description: "which environment to deploy", defaultValue: "DEV")
    }
    stages{
        stage("Parameter Demo"){
            steps{
                echo "booleanParam is set to ${params.enable_service}"
            }
        }
    }
}