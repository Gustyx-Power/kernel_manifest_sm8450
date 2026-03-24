#  OSS Kernel Manifest

Manifest for building kernel with custom toolchain and CLO prebuilts on SM8450.

### 1. Initialize Repositories Kernel
```bash
repo init -u https://github.com/Gustyx-Power/kernel_manifest_sm8450.git -b oss-lineage-23.2 
```

### 2. Sync Repositories Source
```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
