node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("knpatel5900/hello-world")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
