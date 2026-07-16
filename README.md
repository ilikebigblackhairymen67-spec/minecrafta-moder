# Minecraft Forge 1.19.2 Mod

Automated GitHub Actions workflow to compile ZIP files to JAR for Minecraft Forge 1.19.2 mods.

## Features

- ✅ Automatic builds on push/pull requests
- ✅ Java 17 JDK setup
- ✅ Gradle-based compilation
- ✅ ZIP extraction and compilation
- ✅ JAR artifact generation
- ✅ Automated releases on tags

## Directory Structure

```
.
├── .github/workflows/
│   └── build.yml          # GitHub Actions workflow
├── src/
│   └── main/
│       ├── java/          # Java source files
│       └── resources/     # Resource files
├── build.gradle           # Gradle configuration
├── settings.gradle        # Gradle settings
└── README.md
```

## Setup

1. **Upload your mod source** - Place ZIP files in `src/` directory
2. **Push to GitHub** - The workflow runs automatically
3. **Check Actions tab** - Monitor build progress
4. **Download JAR** - Get compiled JAR from Artifacts

## Creating a Release

Tag your commit to auto-create a release with JAR:

```bash
git tag v1.0.0
git push origin v1.0.0
```

## Minecraft Forge 1.19.2 Requirements

- Java 17+
- Forge MDK for 1.19.2
- Gradle 7.0+

## License

Customize as needed for your mod!