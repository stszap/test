node {
   stage("test"){
      jiraSendDeploymentInfo(environmentId: "staging-${currentBuild.startTimeInMillis}", environmentName: "Staging", environmentType: 'staging', state: 'successful', changeSet: ["SUP-3", "SUP-4"])
   }
}
