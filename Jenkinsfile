node {

    stage 'Checkout'

    git url: 'https://github.com/qwazr/parent.git'

    stage 'Build'

    withMaven() {
        sh "mvn clean deploy"
    }
}