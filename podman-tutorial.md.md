# Panduan Pemula untuk Podman: Container Runtime tanpa Daemon

![Podman Logo](https://podman.io/images/podman.svg)

## Apa itu Podman?
**Podman** (Pod Manager) adalah container engine open-source yang dirancang sebagai alternatif modern untuk Docker. Keunggulan utamanya:
- 🔐 **Rootless**: Jalankan container tanpa privilege root
- 🚫 **Daemonless**: Tidak perlu background process
- 📦 **Docker-compatible**: Mendukung OCI images dan Docker CLI

## Instalasi Podman
### Ubuntu/Debian
```bash
sudo apt-get update
sudo apt-get install podman