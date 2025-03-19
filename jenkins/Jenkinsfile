pipeline{
    agent any
    parameters{
        booleanParam(name: "enable_service", description: "Enable Service", defaultValue: false)
        string(name: "version", description: "specify a version", defaultValue: "v1.0")
        choice(name: "environment", choices: ["DEV", "STAGE", "PROD"], description: "which environment to deploy")
    }
    stages{
        stage("Parameter Demo"){
            steps{
                echo "booleanParam is set to ${params.enable_service}"
                echo "string is set to ${params.version}"
                echo "choice is set to ${params.environment}"
            }
        }
    }
}