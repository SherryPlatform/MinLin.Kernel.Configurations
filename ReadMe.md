# MinLin.Kernel.Configurations

Configurations for Linux Kernel used in MinLin, a minimal bootable generic Linux
environment for specific platforms.

If you are looking for a ready-to-use kernel tree, have a look at
https://github.com/SherryPlatform/MinLin.Kernel.

## Flavors

### Hyper-V Generation 2 Virtual Machines

You can choose these configurations for Azure, Hyper-V and NanaBox.

Note: NanaBox is a third-party lightweight XAML-based out-of-box-experience 
oriented Hyper-V virtualization software based on Host Compute System API, 
Remote Desktop ActiveX control and XAML Islands, project repository available
at https://github.com/M2Team/NanaBox. NanaBox is the reference and prototype
virtualization platform for MinLin.

- [x64, generic, as modularized as possible](MinLin/config-x64-NanaBox)
- [x64, generic, make essential modules builtin](MinLin/config-x64-NanaBox.Medium)
- [x64, generic, make all modules builtin](MinLin/config-x64-NanaBox.Single)

- [arm64, generic, as modularized as possible](MinLin/config-arm64-NanaBox)
- [arm64, generic, make essential modules builtin](MinLin/config-arm64-NanaBox.Medium)
- [arm64, generic, make all modules builtin](MinLin/config-arm64-NanaBox.Single)

## Usage

You can set KCONFIG_CONFIG variable to one of these configuration files from
this repository when you building your Linux Kernel.

## License

MinLin.Kernel.Configurations is distributed under the same license from Linux
Kernel because this is the Linux Kernel configurations. For more information,
have a look at https://github.com/torvalds/linux/blob/master/COPYING.
