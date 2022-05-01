# Command Line Wallets

Solana supports several different types of wallets that can be used to interface directly with the Solana command-line tools.

To use a Command Line Wallet, you must first [install the Solana CLI tools](https://docs.solana.com/cli/install-solana-cli-tools)

### File System Wallets

A _file system wallet_, aka an FS wallet, is a directory in your computer's file system. Each file in the directory holds a keypair.

### File System Wallet Security

A file system wallet is the most convenient and least secure form of wallet. It is convenient because the keypair is stored in a simple file. You can generate as many keys as you would like and trivially back them up by copying the files. It is insecure because the keypair files are **unencrypted**. If you are the only user of your computer and you are confident it is free of malware, an FS wallet is a fine solution for small amounts of cryptocurrency. If, however, your computer contains malware and is connected to the Internet, that malware may upload your keys and use them to take your tokens. Likewise, because the keypairs are stored on your computer as files, a skilled hacker with physical access to your computer may be able to access it. Using an encrypted hard drive, such as FileVault on macOS, minimizes that risk.

<mark style="color:green;"></mark>[<mark style="color:green;">File System Wallet</mark>](https://docs.solana.com/wallet-guide/file-system-wallet)&#x20;
