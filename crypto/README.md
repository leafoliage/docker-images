# Crypto

This is an environment for CTF crypto challenges, with sagemath and jupyter installed.

## Usage

To build the image.

```sh
just build
```

To run this container.

```sh
just run
```

To stop this container.

```sh
just stop
```

To enter container's shell.

```sh
just sh
```

To enter container's shell as different user.

```sh
just sh root
```

## Config

Container/Image parameters can be set in the `justfile`.

|param|default|description|
|-----|-------|-----------|
|image|crypto|built image name|
|container|crypto-1|container name|
|port|8888|exposed jupyter notebook port|
|bind_src|$(pwd)|bind volume source|
|bind_dst|/home/sage/work|bind volume destination|
