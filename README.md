<div align='center'>
  <h1>gorvus</h1>
  <p>gorvus is a command-line interface (CLI) tool written in Go that simplifies the process of generating Dockerfiles and docker-compose.yml files for your projects. With gorvus, you can quickly scaffold Docker configurations without manual editing, saving time and effort.</p>
  <img src='https://img.shields.io/github/languages/top/FelipeMCassiano/gorvus' alt='GitHub top language' />
  <img src='https://img.shields.io/github/last-commit/FelipeMCassiano/gorvus' alt='GitHub last commit' />
</div>

## Features

- **Dockerfile Generation**: Generate Dockerfiles for your projects with ease.
- **docker-compose.yml Generation**: Coming soon...
- **Customizable Templates**: Configure templates to suit your project's specific requirements.
- **Command-line Interface**: Use an intuitive and fancy interface to maximize your experience.

## Installation

To install gorvus, you need to have Go installed on your system. Then, you can install it using the following command:

```bash
go install github.com/FelipeMCassiano/gorvus/cmd@latest
```

## Usage

Once installed, you can use gorvus to generate Dockerfiles and docker-compose.yml files for your projects.

### Generate Dockerfile

```bash
gorvus createDockerfile --language<language> --projectName<projectName>
```

> [!NOTE]
> Currently, only the languages Go and Rust supports Dockerfile generation.

### Generate docker-compose.yml (Coming Soon)

The feature to generate a docker-compose.yml file will be available soon. Stay tuned for updates!

## Contributing

If you're interested in contributing to this project, consider reading the [Contributing Guide](CONTRIBUTING.md)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
