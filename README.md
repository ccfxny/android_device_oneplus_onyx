#Device tree for OnePlus X

###Syncing repo
Add this to your localmanifest
```xml
<manifest>
  <project name="ccfxny/android_device_oneplus_onyx" path="device/oneplus/onyx" remote="github" revision="mokee"/>
  <project name="Mokee/android_device_oppo_common" path="device/oppo/common" remote="github" revision="mkl-mr1" />
  <project name="ccfxny/android_kernel_oneplus_msm8974" path="kernel/oneplus/onyx" remote="github" revision="5.1.1" />
  <project name="ccfxny/android_vendor_oneplus_onyx" path="vendor/oneplus/onyx" remote="github" revision="oxy212" />
  <project name="Mokee/android_device_qcom_common" path="device/oppo/common" remote="github" revision="mkl-mr1" />
  <project name="Mokee/android_hardware_qcom_fm" path="hardware/qcom/fm" remote="github" revision="mkl-mr1" />
</manifest>
```

###Building
```bash
. build/envsetup.sh
lunch mk_onyx-(eng|userdebug|user)
mka bacon
```
