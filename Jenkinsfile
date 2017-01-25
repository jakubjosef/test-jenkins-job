stage("Mirror") {
  node() {
          checkout changelog: true, poll: true, 
            scm: [$class: 'GitSCM', branches: [[name: 'master'],[name: 'duky']], doGenerateSubmoduleConfigurations: false,  submoduleCfg: [], userRemoteConfigs: [[url: SOURCE_URL]]]
  }
}
