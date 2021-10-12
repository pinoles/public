A Python wrapper that runs Terraform on (currently) AWS, fires up a specified number of instances
  (the instance types are currently hardcoded, but that's an easy enough fix), and takes the
  (currently) public IP of the instances created, feeds them into a host file, and runs an Ansible script
  that configures an initial user with SSH keys and sudoers entry.
