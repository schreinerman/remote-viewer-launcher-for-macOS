# remote-viewer launcher for macOS
 
remote-viewer launcher for macOS, requires remote-viewer installed via brew

See also: https://gist.github.com/tomdaley92/789688fc68e77477d468f7b9e59af51c

## Proxmox - SPICE client setup for MacOS

1. Install a working (and compiled) version of [virt-viewer](https://www.spice-space.org/osx-client.html). You may view the homebrew package's upstream source on [GitHub](https://github.com/jeffreywildman/homebrew-virt-manager).

    ```bash
    brew tap jeffreywildman/homebrew-virt-manager
    brew install virt-viewer
    ```

2. Once that's installed should be able make a call `remote-viewer` with a _pve-spice.vv_ file downloaded from proxmox web interface
    ```bash
    remote-viewer pve-spice.vv
    ```

3. Download and install Remote Viewer.app from the releases page into your Applications folder