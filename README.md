# Ansible

# Links
* [How to Install and Configure latest version of Ansible on Ubuntu Linux](https://www.cyberciti.biz/faq/how-to-install-and-configure-latest-version-of-ansible-on-ubuntu-linux/)
* [Installation - Semaphore Docs](https://docs.ansible-semaphore.com/administration-guide/installation)

# setting up Semaphore
* create a semaphore user on the host and set to sudoer
* Add the ansible host to the semaphore user's ssh authorized_keys
* Add the semaphore user to visudo under the default property:  semaphore ALL=(ALL) NOPASSWD: ALL
