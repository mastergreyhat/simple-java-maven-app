pipeline{
    agent any
    parameters{
        booleanParam(name: "enable_service", description: "Enable Service", defaultValue: false)
        string(name: "version", description: "specify a version", defaultValue: "v1.0")
        choice(choices: ["DEV", "STAGE", "PROD"], description: "which environment to deploy", defaultValue: "DEV")
    }
    stages{
        stage("Parameter Demo"){
            steps{
                echo "booleanParam is set to ${params.enable_service}"
                echo "string is set to ${params.environment}"
                echo "choice is set to ${params.choice}"
            }
        }
    }
}