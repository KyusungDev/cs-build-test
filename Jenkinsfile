library identifier: 'yanolja-pipeline-library', changelog: false

def awsProfile = 'dev'
def destinationBucket = 'yanolja-dev-image-bucket/iot-admin-site-dev.yanolja.com'
def applicationPath = 'dist/'
def distributionId = 'E3KPT5NU9ZBC8R'

publishBasePipeline slackChannels: ['#'], {
    stage('Checkout') {
        checkout scm
    }
   
}
