# node-and-docker-basics

## 1. Build command

```bash
docker build .
```

#### OR build with tag

```bash
docker build -t repo/node-and-docker-basics:latest .
```

## 2. Run command

> running "docker build ." will give you Successfully built b01f993c13df.

> now to run it use

```bash
docker run -p 8080:8080 b01f993c13df
```

#### OR

> running "docker build -t repo/node-and-docker-basics:latest ." will give you Successfully built b01f993c13df Successfully tagged repo/node-and-docker-basics:latest.

> now to run it use

```bash
docker run -p 8080:8080 repo/node-and-docker-basics
```
