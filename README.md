# Passy RPM Repo

This repo serves `.rpm` packages for the **Passy** CLI.

## 🧪 Usage (Fedora/RHEL/CentOS)

```bash
sudo tee /etc/yum.repos.d/passy.repo <<EOF
[passy]
name=Passy CLI
baseurl=https://ocheops.github.io/passy-rpm-repo
enabled=1
gpgcheck=0
EOF

sudo dnf install passy
```

## 📦 Maintainer
[OcheOps](https://github.com/OcheOps)
