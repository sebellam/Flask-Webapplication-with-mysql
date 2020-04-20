node {

    checkout scm

    docker.withRegistry('https://hub.docker.com', 'dockerseshu') {

        def customImage = docker.build("seshubellamkonda/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
