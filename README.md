### Sony Mobile's vendor blobs for AOSP

`find . -name "*.mk" -print | xargs sed -i 's|(TARGET_OUT)/vendor|(TARGET_OUT_VENDOR)|g'`
