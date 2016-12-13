node {

    stage 'Checkout'

    git url: 'https://github.com/qwazr/parent.git'

    stage 'Build'

    withMaven(maven: 'Maven') {
        sh "mvn clean deploy"
    }
}
