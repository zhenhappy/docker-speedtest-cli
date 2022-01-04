# docker: speedtest-cli

This is a docker image to run the [speedtest-cli commandline tool](https://github.com/sivel/speedtest-cli)
for benchmarking ISP performance.

### Build from docker file

If you want to build the docker container image yourself you can do so with the
following commands:

```bash
git clone git@github.com:zhenhappy/docker-speedtest-cli.git
cd docker-speedtest-cli
docker build -t speedtest-cli .
```

### Pulling from docker hub

If you just want to obtain the image from the docker registry, you can use the
following command:

```bash
docker pull zhenhappy/speedtest-cli
```

### Running the command line tool

In order to run the speedtest-cli command line just use the following:

```bash
docker run --rm zhenhappy/speedtest-cli
```

Any parameters that you can pass to the `speedtest-cli` command can be added to that line.

```bash
docker run --rm zhenhappy/speedtest-cli --help
```
