node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'DockerHubCred') {

        def customImage = docker.build("chandana48/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
