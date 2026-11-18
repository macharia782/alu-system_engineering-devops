# SSH

Bash scripts and client configuration files for creating RSA key pairs, configuring passwordless SSH authentication, and connecting to a remote Ubuntu server.

## Files
* `0-use_a_private_key` - Connects to the remote server using the `~/.ssh/school` private key.
* `1-create_ssh_key_pair` - Generates a 4096-bit RSA key pair named `school` protected by a passphrase.
* `2-ssh_config` - SSH client configuration enforcing key-based authentication (`~/.ssh/school`) and disabling password authentication.
