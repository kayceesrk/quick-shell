# quick-shell
Spawn a shell by creating a tunnel to the container running GitHub Actions workflow

## Usage
- Fork this repo
- Click on `Actions` tab
- Select `Spawn a shell` workflow
- Click on `Run workflow` button
- Choose Runner
- Choose Authenticated Access
  - Checked: Tunnel can be accessed only from the device having SSH access to your GitHub account.
  - Unchecked: Tunnel can be accessed from any device and also from the browser.
- Click on `Run workflow` button
- Check logs for access url

NOTE: If you see a blank shell, press `q` key.

# Runners
| Runner | Operating System | Architecture | Processor (CPU) | Memory (RAM) | Storage (SSD) |
| - | - | - | - | - | - |
| ubuntu-22.04 | Ubuntu | x86_64 | 2 | 7 GB | 14 GB |
| ubuntu-20.04 | Ubuntu | x86_64 | 2 | 7 GB | 14 GB |
| macos-13 | MacOS | x86_64 | 4 | 14 GB | 14 GB |
| macos-12 | MacOS | x86_64 | 3 | 14 GB | 14 GB |
| macos-11 | MacOS | x86_64 | 3 | 14 GB | 14 GB |
| windows-2022 | Windows | x86_64 | 2 | 7 GB | 14 GB |
| windows-2019 | Windows | x86_64 | 2 | 7 GB | 14 GB |
