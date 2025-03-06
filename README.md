# 🚀 Cyfrinup  

**The all-in-one security toolkit** for downloading Command Line tools from Cyfrin.  

> [!CAUTION]
> It is under development and is not fully tested. Please do not use it yet. It may lead to unrecoverable changes.

### ✅ Supported Platforms  
- Linux  
- macOS  
- WSL  

⚠️ Windows native users cannot use Cyfrinup and should manually download supported tools from their respective repositories.  

## 🛠 Installation  

Run the following command to install Cyfrinup:  

```bash
curl -L https://raw.githubusercontent.com/Cyfrin/up/main/install | bash
```

## 📦 Tools Included  

| Tool      | Description | Supported Platforms |
|-----------|------------|--------------------|
| [Aderyn](https://github.com/Cyfrin/aderyn) | Rust based Solidity AST security scanner | Linux, macOS, WSL |
| [Safe-Hash](https://github.com/Cyfrin/safe-hash-rs) | Safe Wallet Tx Verificaton tool | Linux, macOS, WSL, Windows (Intel) |


## 🚀 Usage  

After installation, run the following command to download all available tools:  
```bash
cyfrinup
```  
This will fetch and install all supported tools for your platform. 🚀
