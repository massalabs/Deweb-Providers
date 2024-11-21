# Deweb Providers

This GitHub repository is a collection of DeWeb providers that can be used by people and tools to allow users to access websites stored on the Massa Blockchain. For more information about DeWeb, please visit the [Massa DeWeb Documentation](https://docs.massa.net/docs/deweb/home).

## Adding a Provider

To add your DeWeb provider to this repository, please follow these steps:

1. Create a new YAML file in the `providers` directory.
2. Name the file to match your provider's name.
3. Ensure the file follows the format specified in `schema.yaml`.
4. Submit a pull request with your new file.
5. The pull request will be tested by the CI pipeline to ensure it is valid.
6. If your pull request is valid, it will be reviewed by the Massa team and merged.

### Example Provider File

Here is an example of a provider file:

```yaml
title: Example Provider
url: https://example.com
desc: An example provider for the Massa DeWeb project.
owner: Example Company
contact:
  email: contact@example.com
  telegram: example
```

You can also take example on the existing providers in the `providers` directory.

## Accessing the Full List of Providers
Developers can access the full list of providers using the raw file available at the following URL:

https://github.com/massalabs/Deweb-Providers/raw/refs/heads/main/providers.yaml
