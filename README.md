# vmproxy
Tailscale Proxy for VNC and libvirt virsh control over a VM

This repository contains a tsnet Tailscale proxy that allows you to expose a VM via VNC on your Tailnet. Additionally,
you can SSH into the tsnet application and control the VM via virsh commands like Stop, Start, Restart, Pause, and
Resume.

The code in this repository is experimental and is provided without any warranty. However, it should be relatively easy
to adapt for your own use.

## Contributing

Contributions to this project are welcome. Please feel free to open an issue or submit a pull request if you have any improvements or bug fixes to suggest.

## License

This project is licensed under the [MIT License](LICENSE).
