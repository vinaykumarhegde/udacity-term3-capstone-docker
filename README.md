udacity-term3-capstone-docker
---

Uses Udacity docker file with tf gpu

Buid:

```
nvidia-docker build . -t vnayin/udacity-term3-capstone-docker:latest
```

Run:
```
 nvidia-docker run -it -v $(realpath .):/project  vnayin/udacity-term3-capstone-docker
 ```

