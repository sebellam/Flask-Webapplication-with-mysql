node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockercred') {

        def customImage = docker.build("seshubellamkonda/dockerwebapp2")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
