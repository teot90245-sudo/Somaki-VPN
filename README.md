
name: Somako VPN Build

on:
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Check source
        run: |
          echo "Somako VPN build environment is ready"

