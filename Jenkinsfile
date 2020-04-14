properties([
  buildDiscarder(logRotator(daysToKeepStr: '7', numToKeepStr: '7')),
  disableConcurrentBuilds(),
  pipelineTriggers([cron('*/5 * * * *')])
])


node {

  stage("build") {
    echo "building..."
  }

}
