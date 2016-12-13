node{
    stage 'Checkout'

    git url: 'https://github.com/qwazr/qwazr-parent.git'

    stage 'Build'

    withMaven() {
        sh "mvn clean install"
    }
}
