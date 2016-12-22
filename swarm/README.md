## SWARM

### Requirements

#### "Just clone the repo and build"

* `docker`

#### "I got a fork I want to package into an image"

* `docker`
* Go language
* Have `$GOPATH` defined
* Have your cloned repo in the right path (i.e. `$GOPATH/src/github.com/ethereum`)

### Building the image

Run in this directory the file

```
./build-image.sh
```

Will invoke `docker build` and package your swarm image into an alpine container.

If you need to package from a fork, take a loog at the code of the executable above.
You need to comment / uncomment a couple of lines to accomplish that goal.

### Running the image

(TODO)

### Testing your image

(TODO) 