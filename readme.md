# Local Docker Deployment with Terraform

This repository contains Terraform configurations to automate the deployment of Docker containers locally in linux system. The configurations are designed to be easy to understand, modify, and deploy, ensuring a streamlined experience for both beginners and experts alike.

## 📋 Table of Contents

- [Prerequisites](#prerequisites)
- [Quick Start](#quick-start)
- [Repository Structure](#repository-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## 🔍 Prerequisites

Before you can use these configurations, please ensure you have the following software installed:

- [Docker](https://www.docker.com/get-started)
- [Terraform](https://learn.hashicorp.com/terraform/getting-started/install.html)

## 🚀 Quick Start

1. **Clone the Repository**

    ```bash
    git clone https://github.com/Paramvir12121/terraform-docker-local.git
    cd local-docker-terraform
    ```

2. **Initialize Terraform**

    ```bash
    terraform init
    ```

3. **Apply Terraform Configuration**

    ```bash
    sudo terraform apply
    ```

    After executing the above command, you'll be prompted to confirm the actions. Type `yes` to proceed.
    

4. Once deployment is successful, you should see your Docker containers running.

## 📁 Repository Structure

- `main.tf`: The primary configuration file where resources are defined.
- `variables.tf`: Contains variable definitions.
- `outputs.tf`: Configurations related to output after `terraform apply`.
- `assets/`: Directory for assets like images.
  
## 🔧 Customization

You can customize the Docker containers you wish to deploy by modifying the indiviual terrraform `main.tf` files in each folder. Ensure that you update the configurations as per your requirements.

## 👥 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

<!-- ## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details. -->

---

For more information or support, please refer to the official Terraform and Docker documentation or raise an issue in this repository.
