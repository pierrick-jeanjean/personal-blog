# personal-blog
Jekyll based blog to log everything I am discovering during and outside my work

## Run locally
To run the site locally, there is a need to build the image with the Dockerfile-local

```bash
docker build -f Dockerfile-local -t personal-blog .
```

Then, run it

```bash
docker run --rm -p 4000:4000 -p 35729:35729 -v ${PWD}:/srv/jekyll personal-blog
```
