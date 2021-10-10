node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/repositories', 'DockerID') {

        def customImage = docker.build("abhishek/testapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
