# tenseoverflow's infrastructure

I manage a Fedora NAS server. [I used to manage 4 Ubuntu LTS Oracle Cloud instances](http://hen.ee/dont-trust-oracle-cloud-free-tier/).

### Software (currently)

- [Nextcloud](https://nextcloud.com)
- [Jellyfin](https://jellyfin.org/)
- [Home Assistant](https://www.home-assistant.io/)
- [Homarr](https://homarr.dev/)
- Maybe more in the future.

I try to use Podman where I see fit. Podman has numerous benefits when it comes to service management. Podman is daemonless, rootless and utilises SystemD unit files. This allows it to auto update and leaves management to SystemD. Podman also integrates well with SELinux.

**NB: These files change and might not work in all environments. Please use them with caution.**
