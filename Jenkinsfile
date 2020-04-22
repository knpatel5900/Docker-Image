node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("kishan/hello-world")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
