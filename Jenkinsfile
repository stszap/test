node {
   stage("test"){
      jiraSendDeploymentInfo(environmentId: "staging-${currentBuild.startTimeInMillis}", environmentName: "Staging", environmentType: 'staging', state: 'successful', changeSet: ["some thing or other SUP-3 ssd", "blip blop SUP-4 commit msg"])
   }
}
