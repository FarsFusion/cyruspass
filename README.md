# CyrusPass 🦁

**Secure & Customizable Password Generator**  
*Inspired by Cyrus the Great's Legacy of Strength and Unity*

---

![HomePage](/images/logo.png)

## Features ✨

- 🎱**Password Types**: Cyrus Pass (mixed high-quality), Secure, UUID, Base64, Strong, Basic, Hex, Custom
- 🔒 **Military-Grade Security**: Uses `/dev/urandom` and cryptographic functions
- 🎨 **Colorized Output**: Adaptive terminal theme support (light/dark)
- 🔄 **Interactive Mode**: Fuzzy-find selection with `fzf`
- ⚡ **Live Generation**: Visual typing effect with `pv`
- 🛡️ **Auto-Dependency Installer**: Ensures required tools are present

---

## Quick start 👾

Download package from PPA repo of FarsFusion

**Basic Command**:

```shell
./cyruspass.sh -t [TYPE] -l [LENGTH]
```

**Interactive Mode** (no flags):

```shell
./cyruspass.sh
```

**Examples**:

```shell
# Generate 24-character Cyrus Pass
./cyruspass.sh -t 1 -l 24
```

```shell
# Create 50-character custom password
./cyruspass.sh -t 8 -l 50 -c "★§~%&αβγ"
```

```shell
# Interactive selection (type + length)
./cyruspass.sh
```