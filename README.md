# scoop-bucket

My personal [Scoop](https://scoop.sh/) bucket for Windows applications.

## What is Scoop?

Scoop is a command-line installer for Windows that makes it easy to install and manage applications without the hassle of traditional installers.

## What is a Scoop Bucket?

A Scoop bucket is a collection of app manifests that Scoop can install. This bucket contains my personal applications and tools.

## Installation

To add this bucket to your Scoop installation:

```powershell
scoop bucket add aretw0 https://github.com/aretw0/scoop-bucket
```

## Usage

After adding the bucket, you can install any application from it using:

```powershell
scoop install aretw0/<app-name>
```

To see all available apps in this bucket:

```powershell
scoop search aretw0/
```

To update apps from this bucket:

```powershell
scoop update <app-name>
```

## Contributing

If you find any issues with the manifests in this bucket, please open an issue or submit a pull request.

## License

This repository is licensed under the MIT License. Individual applications may have their own licenses - please check each app's homepage for details.
