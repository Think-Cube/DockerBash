# DockerBash

A minimal Docker image based on Alpine Linux with Bash and essential GNU utilities preinstalled.  
Perfect for scripting, automation, and lightweight shell environments.

## Included Packages

- bash
- gawk
- sed
- grep
- bc
- coreutils

## Usage

### Build the image

```bash
docker build -t docker-bash .
```

## Run the container

```bash
docker run -it docker-bash
```

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contribution

Feel free to contribute by opening issues or pull requests. Your feedback and improvements are highly appreciated!