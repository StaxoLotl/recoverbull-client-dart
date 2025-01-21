# Recoverbull Dart

`recoverbull_dart` is a project designed to facilitate secure backup and recovery of data using encryption and key management techniques. It supports creating encrypted backups, restoring data from backups, and managing keys with a remote server.

## Features

- Create encrypted backups using a provided backup key or BIP85 derived key.
- Restore data from encrypted backups using a provided key or BIP85 derived key.
- Store and recover backup keys on a remote server.
- Supports BIP39 mnemonic phrases for key derivation.
- Utilizes AES encryption with PKCS7 padding for secure data encryption.

## Installation

Add `recoverbull_dart` to your `pubspec.yaml` file:

```yaml
dependencies:
  recoverbull_dart:
    git:
      url: https://github.com/StaxoLotl/recoverbull-dart.git
      ref: master