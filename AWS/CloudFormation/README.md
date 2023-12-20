# Documentation

## Common
- It is assumed that a public key is avalible Amazon EC2 ([Create key pairs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/create-key-pairs.html#create-key-pair-cloudformation)).

## Kali

- By default, [linux-cf-tweak.yml](Kali/linux-cf-tweak.yml) makes changes to security groups to allow TCP 80 and 443.
- The Linux distribution can be edited in [linux-cf-instances.yml](Kali/linux-cf-instances.yml) (default Kali).

## Windows

- By default, [windows-cf-tweak.yml](Windows/windows-cf-tweak.yml) makes changes to security groups to allow TCP 80 and 443.
- The Windows distribution can be edited in [windows-cf-instances.yml](Windows/windows-cf-instances.yml) (default Windows Server 2022).

# To-Do

## Windows
- [ ] Disable Windows Defender via PowerShell during deployment
- [ ] Install Tailscale
- [ ] Log on Tailscale


## Kali
- [ ] Update and update to the latest version during deployment.
- [ ] Installation of default pakages
- [ ] Configuration of default pakages
- [ ] Install Tailscale
- [ ] Log on Tailscale
