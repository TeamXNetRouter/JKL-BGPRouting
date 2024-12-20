<h1 align="center">
  <br>
    <img src="pict/logo.png" alt="logo" width="200">
</h1>

# BGP Routing
Welcome to the BGP Routing Repository. This documentation will guide you through understanding and setting up BGP Routing on your system. You will find all the necessary information and tools in this comprehensive guide.

## Table of Contents
1. [Configuration](#configuration)
2. [Prerequisites](#prerequisites)
3. [Steps](#steps)

# Configuration
<h1 align="center">
  <br>
    <img src="pict/configuration.png" alt="configuration" width="1000">
</h1>

# Prerequisites
Before proceeding with the setup, ensure that you have the following prerequisites:

1. **Ubuntu**: If you are using Windows, you can download Ubuntu from:
    [Ubuntu](https://ubuntu.com/desktop/wsl)

2. **Mininet**: Download Mininet from:
    [Mininet](https://mininet.org/)

3. Navigate to the Mininet directory:

    ```bash
    cd mininet
    ```

4. Install all Mininet dependencies by running the following command:

    ```bash
    ./util/install.sh -a
    ```

5. Once the installation is complete, you can proceed with the next steps.

# Steps
Follow the instructions below to get the system up and running:

1. Clone the repository:

    ```bash
    git clone https://github.com/TeamXNetRouter/JKL-BGPRouting.git
    ```

2. Navigate to the project directory:

    ```bash
    cd JKL-BGPRouting
    ```

3. Run the project using the following command:

    ```bash
    sudo python3 bgp-lab.py -c frr-config
    ```

4. To test the setup, you can use the following command in the terminal:

   Notes: We apologize that these steps cannot be performed because our existing frr.conf cannot be read by our code. You can test it by reconfiguring manually according to our configuration.

    ```bash
    C11 traceroute -n C33
    ```
