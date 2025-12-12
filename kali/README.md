# Crypto

This is a kali environment for cyber security practice.

## Usage

To build the image.

```sh
just build
```

To run this container and enter the environment.

```sh
just run
```

To cp file into the container.

```sh
just cp <file> <dst>
# default dst is /
```

## Config

Container/Image parameters can be set in the `justfile`.

|param|default|description|
|-----|-------|-----------|
|image|kali|built image name|
|container|kali-1|container name|
