# Minecraft Mod Compiler

Super simple workflow - just add your Java files and it compiles to JAR!

## How to Use

### Method 1: Direct Java Files (Easiest)
1. Create folders in your repo:
   ```
   src/main/java/
   ```

2. Add your `.java` files there

3. Push to GitHub → Automatically compiles to JAR

### Method 2: Upload ZIP
1. Create `src/` folder

2. Put your mod source ZIP in there

3. Push → Workflow extracts & compiles

### Method 3: Just Drop Java Files Anywhere
1. Add `.java` files anywhere in your repo

2. Push → Finds and compiles them automatically

## Get Your JAR

- Go to **Actions** tab
- Click the latest build
- Download from **Artifacts** → `minecraft-mod.jar`

## Create a Release (Optional)

Tag your commit and it auto-releases on GitHub:
```bash
git tag v1.0.0
git push origin v1.0.0
```

Done! 🚀
