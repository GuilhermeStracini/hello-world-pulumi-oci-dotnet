# Hello World Pulumi over OCI with .NET

📚 A repository to learn **[Pulumi](https://www.pulumi.com/)**, a modern Infrastructure-as-Code (IaC) tool, using **OCI (Oracle Cloud Infrastructure)** as the cloud provider and **C# (.NET)** as the programming language.

---

## Overview

This repository demonstrates how to use Pulumi with OCI and .NET for building and managing cloud infrastructure. It includes examples for provisioning resources, configuring OCI services, and leveraging Pulumi's features for infrastructure management and automation.

---

## Features

- **Infrastructure-as-Code (IaC)**:
  - Use C# to define and provision OCI resources programmatically.
  - Leverage Pulumi's type-safe SDK for .NET.

- **Oracle Cloud Infrastructure**:
  - Provision and manage services like Compute, OKE (Kubernetes), VCN (Virtual Cloud Network), and more.

- **Continuous Delivery (CD)**:
  - Integrate with GitHub Actions using the Pulumi GitHub App for automated deployment.

- **Hands-On Examples**:
  - Demonstrates key Pulumi features such as state management and multi-environment support.

---

## Getting Started

### Prerequisites

- **Pulumi CLI**: Install from [Pulumi's official site](https://www.pulumi.com/docs/get-started/install/).
- **.NET SDK**: Download the latest version from [Microsoft's .NET site](https://dotnet.microsoft.com/).
- **OCI CLI**: Set up the [OCI Command Line Interface](https://docs.oracle.com/en-us/iaas/Content/API/SDKDocs/cliinstall.htm) and configure your credentials.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GuilhermeStracini/hello-world-pulumi-oci-dotnet.git
   cd hello-world-pulumi-oci-dotnet
   ```

2. **Install Dependencies**:
   ```bash
   dotnet restore
   ```

3. **Set Up Pulumi**:
   - Log in to Pulumi:
     ```bash
     pulumi login
     ```
   - Configure your Pulumi stack:
     ```bash
     pulumi config set oci:region <your-oci-region>
     ```

4. **Run the Project**:
   - Preview the changes:
     ```bash
     pulumi preview
     ```
   - Deploy the stack:
     ```bash
     pulumi up
     ```

5. **Destroy the Stack** (Optional):
   - Remove all provisioned resources:
     ```bash
     pulumi destroy
     ```

---

## Useful Links

Explore additional resources to deepen your understanding of Pulumi and OCI:

- [Pulumi Official Website](https://www.pulumi.com/)
- [Pulumi OCI Provider Documentation](https://github.com/pulumi/pulumi-oci)
- [Pulumi GitHub App](https://www.pulumi.com/docs/using-pulumi/continuous-delivery/github-app/)
- [Using GitHub Actions with Pulumi for Continuous Delivery](https://www.pulumi.com/docs/using-pulumi/continuous-delivery/github-actions/)
- [Pulumi .NET Tools](https://www.pulumi.com/docs/languages-sdks/dotnet/)
- [OCI OKE (Kubernetes) with Pulumi](https://docs.oracle.com/en/learn/oci-oke-pulumi/index.html)
- [OCI Compute with Pulumi](https://docs.oracle.com/en/learn/oci-compute-vcn-pulumi/index.html)

---

## Contribution

Contributions are welcome!  
Feel free to fork this repository, open issues, or submit pull requests to enhance examples or add new ones.

---

## License

This project is licensed under the [MIT License](LICENSE).
