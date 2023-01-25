```bash
$ docker build -t lyrics .
$ docker run --rm --net host -it \
    -v $(pwd):/home/app/src \
    lyrics \
    bash
```
