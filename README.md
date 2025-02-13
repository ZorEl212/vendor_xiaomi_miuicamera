# ANXCamera for Ginkgo AOSP

## ⚠ WARNING: Due to LFS issues, the repository has been moved to GitLab. You can find it [here](https://gitlab.com/ZorEl212/vendor_xiaomi_miuicamera).
### Cloning :
- Clone this repo in vendor/xiaomi/miuicamera in your working directory by :
```
git clone https://github.com/ZorEl212/vendor_xiaomi_miuicamera -b anx-ginkgo vendor/xiaomi/miuicamera
```

Make these changes in **device.mk**

**device.mk**
```
# MiuiCamera
$(call inherit-product, vendor/xiaomi/miuicamera/config.mk)
```
## Credits

### Original mod - https://github.com/h1toru/ANXCameraT

