# WIP

## Sample roomservice.xml

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <remote   name="fairphone" 
            fetch="https://gerrit-public.fairphone.software"
            revision="kernel/11/fp4" />

    <project remote="fairphone" path="kernel/fairphone/msm-4.19/kernel/msm-4.19" name="kernel/msm-4.19"/>
    <project remote="fairphone" path="kernel/fairphone/msm-4.19/kernel/msm-4.19/techpack/audio" name="platform/vendor/opensource/audio-kernel" />
    <project remote="fairphone" path="kernel/fairphone/msm-4.19/kernel/msm-4.19/techpack/camera" name="platform/vendor/opensource/camera-kernel" />
    <project remote="fairphone" path="kernel/fairphone/msm-4.19/kernel/msm-4.19/techpack/data" name="platform/vendor/qcom-opensource/data-kernel" />
    <project remote="fairphone" path="kernel/fairphone/msm-4.19/kernel/msm-4.19/techpack/display" name="platform/vendor/opensource/display-drivers" />
    <project remote="fairphone" path="kernel/fairphone/msm-4.19/kernel/msm-4.19/techpack/video" name="platform/vendor/opensource/video-driver" />
    <project remote="fairphone" path="kernel/fairphone/msm-4.19/kernel/msm-4.19/drivers/staging/wlan-qc/fw-api" name="platform/vendor/qcom-opensource/wlan/fw-api" />
    <project remote="fairphone" path="kernel/fairphone/msm-4.19/kernel/msm-4.19/drivers/staging/wlan-qc/qca-wifi-host-cmn" name="platform/vendor/qcom-opensource/wlan/qca-wifi-host-cmn" />
    <project remote="fairphone" path="kernel/fairphone/msm-4.19/kernel/msm-4.19/drivers/staging/wlan-qc/qcacld-3.0" name="platform/vendor/qcom-opensource/wlan/qcacld-3.0" />
</manifest>
```

