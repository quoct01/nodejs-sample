
node {
    checkout scm

<<<<<<< HEAD
    docker.withRegistry('https://hub.docker.com','dockerhub') {
=======
>>>>>>> 39db0e0c6888097c3bc589f752a50c0f372e0961

    docker.withRegistry('https://registry.hub.docker.com','dockerhub') {
        def customImage = docker.build("quoct01/nodejstest")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
