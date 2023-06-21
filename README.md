# squid-playbook

This repository contains an Ansible playbook for automating the installation and configuration of Squid proxy server on Linux machines.

# Prerequisites

Ansible: Ensure that Ansible is installed on the control machine.
Target Machines: Make sure you have target machines running a Linux distribution where you want to install and configure Squid.

# Usage


1 - Clone the repository to your local machine.

2 - Update the inventory.ini file with the IP addresses or hostnames of your target machines.

3 - Customize the squid.conf.j2 template file if needed to adjust Squid's configuration.

4 - Run the playbook using the following command:

    ansible-playbook -i inventory.ini squid-playbook.yml

5 - Sit back and relax as Ansible takes care of installing and configuring Squid on the target machines.


# Contributing

If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

# License

This project is licensed under the MIT License.


# Acknowledgements


I would like to thank the Institute of Computer Science for providing us with the opportunity to work on this project.

Feel free to modify and customize the content based on your specific project details and requirements.
