# Example of working with React App using Docker (HMR enabled)

## Using Docker

Run:

```
// Build docker image
> ./scripts/docker-build

// Run docker container
> ./scripts/docker-run
```

You should see in the terminal react application running in interactive mode:

```
Compiled successfully!

You can now view react-docker in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://172.17.0.2:3000

Note that the development build is not optimized.
To create a production build, use yarn build.
```

## Using docker-compose

Run:

```
> docker-compose up
```

To quit the process use `CTRL + c`.

## Working with containers and images

To list and then remove existing container and image:

```
// List containers
> docker ps -a

// Remove container by ID
> docker rm <ID>

// List images
> docker images

// Remove image by ID
> docker rmi <ID>
```
