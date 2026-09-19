# dr1s Tap

## Installation

1. Add the tap:
   ```bash
   brew tap dr1s/tap
   ```

2. Trust the tap:
   ```bash
   brew trust dr1s/tap
   ```

3. Install a cask:
   ```bash
   brew install dr1s/tap/<cask>
   ```

## Casks

### Alacritty

A GPU-accelerated terminal emulator.

After installation, the cask automatically removes Apple’s Quarantine extended attribute from `Alacritty.app` and re-codesigns the app with an ad-hoc signature so it launches without Gatekeeper warnings.
