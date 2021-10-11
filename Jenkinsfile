node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/repositories', 'abhishekrh/Abhi@9503') {

        def customImage = docker.build("abhishek/testapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
