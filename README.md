# Dockerfile Instructions

**FROM Command**
`FROM <image>:<tag>`
```
An `image` will be from docker hub or local reops and `tag` will be the version of image.
```

- example -> FROM Node:16
+ example ->  FROM myregistry.example.com/myimage:latest
 

 ### Create image out of Dockerfile

 `docker build -t <name> .`

 + `-t tag for new namee`
 - `. is showing current file`