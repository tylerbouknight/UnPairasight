# unPairasight: Advanced Vault Encryption for Obsidian

unPairasight supercharges Obsidian's native security capabilities. With features like tag-based file management and AES-256-CBC encryption, unPairasight fills the security gaps in your Obsidian workflow.

**IMPORTANT**: Please, for my sake, backup your vault before using! Tested only on Windows and iOS.

---

## Key Features

- **AES-256-CBC Encryption**: Secure your files with industry-standard encryption.
    
- **Tag-Managed File Selection**: Encrypt or bypass files based on their tags.
    
- **Auto-Encrypt**: Desktop users enjoy the luxury of auto-encryption upon app closure.
  - Beta 1 release implements URI scheme to trigger vault encryption using obsidian://unpairasight#encrypt. This means iOS users can use Shortcuts to set an automation when obsidian closes, to run the URI and "auto" encrypt the vault. 
    

---

## Getting Started

### Installation

To get your hands on UnPairasight, clone this repository and place it in your Obsidian's `plugins` folder.

### Initialization

#### Newbies

1. After installation, you'll be greeted with a modal prompting a password setup.
2. Once set, your vault is now encryptable.

#### Seasoned Users

1. A password prompt pops up upon startup.
2. Input your password to unlock your data and proceed with your Obsidian ventures.

---

## How to Use

### Commands

- **Encrypt Vault**: Manually secure your entire vault.
    
- **Decrypt Vault**: Reveal the contents. Password needed, obviously.
    
- **Purge Password**: Ditch the existing password. Be careful with this one.
    

### Preferences

Hit `Settings > UnPairasight` to fine-tune your encryption tag policies.

---