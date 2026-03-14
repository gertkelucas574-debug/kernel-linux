# Kernels Linux - Coleção para Estudo e Documentação

Este repositório contém uma coleção de kernels Linux extraídos das ISOs oficiais de diversas distribuições Linux. Os kernels foram obtidos exclusivamente para fins de **estudo e documentação** do projeto **Distro Forge Studio**.

## Sobre os Kernels

Todos os kernels neste repositório foram extraídos de ISOs oficiais das respectivas distribuições. Cada pasta contém:

- **vmlinuz** - O kernel Linux compactado
- **initramfs** ou **initrd** - Sistema de arquivos inicial RAM
- **config** - Configuração de compilação do kernel
- **System.map** - Mapa de símbolos do kernel

## Download dos Kernels

Devido ao tamanho grande dos arquivos, os kernels são hospedados no Catbox (serviço de hospedagem de arquivos gratuito).

| Distribuição | Versão | Download |
|--------------|--------|---------|
| Arch Linux (LTS) | Linux LTS | [Baixar](https://files.catbox.moe/wvxd8s.7z) |
| Debian 13 | 6.12.63 | [Baixar](https://files.catbox.moe/3t6fmr.7z) |
| Debian 13 | 6.12.74 | [Baixar](https://files.catbox.moe/qmtcrb.7z) |
| Arch Linux (ZEN) | Kernel ZEN | [Baixar](https://files.catbox.moe/gvry4z.7z) |
| Fedora 43 | 6.17.1 | [Baixar](https://files.catbox.moe/pl8n5k.7z) |
| Ubuntu | 6.17 | [Baixar](https://files.catbox.moe/65j9hw.7z) |
| openSUSE | 6.19.6 | [Baixar](https://files.catbox.moe/w82yug.7z) |
| openSUSE (LTS) | 6.18.16 | [Baixar](https://files.catbox.moe/1mjqvr.7z) |

### Kernels grandes

Os kernels muito grandes para o Catbox (limite 200MB) estão disponíveis no repositório secundário: **[kernel-linux2](https://github.com/lucasgertke11-bot/kernel-linux2)**

- Arch Linux (226MB)
- Gentoo/Calculate (209MB)

## Uso

Estes kernels podem ser utilizados para:

- Compilação de distribuições Linux customizadas
- Criação de ambientes Live CD/USB
- Estudo da estrutura de boot do Linux
- Desenvolvimento de sistemas embarcados
- Documentação técnica

## Como baixar via terminal

```bash
# Baixar todos os kernels
curl -L -o arch-liux-lts.7z https://files.catbox.moe/wvxd8s.7z
curl -L -o Debian-kernel-6.12.63.7z https://files.catbox.moe/3t6fmr.7z
curl -L -o Debian-kernel-6.12.74.7z https://files.catbox.moe/qmtcrb.7z
curl -L -o Kernel-arch-zen.7z https://files.catbox.moe/gvry4z.7z
curl -L -o kernel-fedora.7z https://files.catbox.moe/pl8n5k.7z
curl -L -o kernel-ubuntu.7z https://files.catbox.moe/65j9hw.7z
curl -L -o openSUSE-kernel.7z https://files.catbox.moe/w82yug.7z
curl -L -o openSUSE-kernel-lts.7z https://files.catbox.moe/1mjqvr.7z

# Extrair
for file in *.7z; do 7z x "$file"; done
```

## Créditos

- **Arch Linux** - https://archlinux.org
- **Debian** - https://www.debian.org
- **Fedora** - https://fedoraproject.org
- **Gentoo** - https://www.gentoo.org
- **openSUSE** - https://www.opensuse.org
- **Ubuntu** - https://ubuntu.com

## Aviso legal

Estes kernels são propriedade intelectual de seus respectivos mantenedores e distribuições. Este repositório é mantido apenas para fins educacionais e de documentação do projeto Distro Forge Studio.

Cada distribuição mantém seus kernels sob licenças de código aberto (GPL v2 ou superior). Consulte a documentação de cada distribuição para mais informações sobre licensing.

---

**Distro Forge Studio** - Projeto para criação de distribuições Linux customizadas
