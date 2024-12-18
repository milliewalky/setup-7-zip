[![Build and Test](https://github.com/milliewalky/setup-7-zip/actions/workflows/sample.yml/badge.svg)](https://github.com/milliewalky/setup-7-zip/actions/workflows/sample.yml)

# Setup 7-Zip

This action downloads, unpacks, and configures 7-Zip for use in GitHub Actions workflows. 7-Zip is a free and open-source file archiver. 7-Zip is unpacked under the temporary directory of a runner.

# Usage

<!-- start usage -->
```yaml
- uses: milliewalky/setup-7-zip@v2
  with:
    # 7-Zip release tag from its GitHub Releases page e.g. 24.07.
    # default: latest
    tag: ""
```
<!-- end usage -->

This action appends 7-Zip to a temporary PATH file, so doing this:

```
7z a -t7z {dst}.7z {src}
```

Should do just fine.

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
