# git-fixup

A tool to easily perform git fixup operations.

## Features

- Fixup staged changes to past commits
- Interactive commit selection
- Automatically executes rebase
- Eliminates manual operations like `git rebase -i @~N`

## Installation

### Using Nix

```bash
nix run github:mrsekut/git-fixup
```

### Using Cargo

```bash
cargo install --git https://github.com/mrsekut/git-fixup
```

## Usage

1. Stage your changes

   ```bash
   git add .
   ```

2. Run git-fixup

   ```bash
   git-fixup
   ```

3. Select target commit from the displayed list
4. The tool will automatically create fixup commit and execute rebase
