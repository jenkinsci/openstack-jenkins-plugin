#!/usr/bin/env groovy

/* `buildPlugin` step provided by: https://github.com/jenkins-infra/pipeline-library */
buildPlugin(
  useContainerAgent: true,
  failFast: false,
  configurations: [
    [platform: 'linux', jdk: 11],
    [platform: 'linux', jdk: 17],
    [platform: 'windows', jdk: 11],
])
