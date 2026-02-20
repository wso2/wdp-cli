# WSO2 Developer Platform CLI

Boost Developer Efficiency: A CLI for WSO2 Developer Platform

## Installation

Download the wdp cli distribution and install.

### Install via script

#### MacOS, Linux, WSL

```bash
curl -o- https://raw.githubusercontent.com/wso2/wdp-cli/main/scripts/install.sh | bash
```

#### Windows

```bash
iwr https://raw.githubusercontent.com/wso2/wdp-cli/main/scripts/install.ps1 -useb | iex
```

### Download from GitHub

Download the appropriate version from the [releases](https://github.com/wso2/wdp-cli/releases) wdp cli github repository

## Getting started

1. Sign into your WSO2 account

```bash
wdp login
```

2. List your projects

```bash
wdp list projects
```

3. Describe your projects/components

```bash
wdp describe <project|component>
```
