# env-secrets-expand

Pure bash script to add Docker secrets as environment variables.

## Usage

It will change all the environment variables with the placeholder {{DOCKER-SECRET:secret-name}} by the content of a secret with the name secret-name when added to the entrypoint.

## Credits

This script is heavily inspired by @bvis (see https://gist.github.com/bvis/b78c1e0841cfd2437f03e20c1ee059fe).
