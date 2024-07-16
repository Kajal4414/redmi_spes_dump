# missi_phoneext4_global-user 13 TKQ1.221114.001 V816.0.2.0.TGCINXM release-keys
- manufacturer: xiaomi
- platform: bengal
- codename: spes
- flavor: missi_phoneext4_global-user
- release: 13
- id: TKQ1.221114.001
- incremental: V816.0.2.0.TGCINXM
- tags: release-keys
- fingerprint: Redmi/spes/spes:13/TKQ1.221114.001/V816.0.2.0.TGCINXM:user/release-keys
- is_ab: true
- brand: Redmi
- branch: missi_phoneext4_global-user-13-TKQ1.221114.001-V816.0.2.0.TGCINXM-release-keys
- repo: redmi_spes_dump

```sh
git clone https://github.com/LineageOS/android_tools_extract-utils tools/extract-utils && git clone https://github.com/LineageOS/android_prebuilts_extract-tools prebuilts/extract-tools && git clone https://github.com/Kajal4414/android_device_xiaomi_spes.git device/xiaomi/spes
```

```sh
bash device/xiaomi/spes/extract-files.sh ./
```

```sh
git clone https://github.com/Kajal4414/android_vendor_xiaomi_spes.git vendor_xiaomi_spes && rm -rf vendor_xiaomi_spes/* && mv vendor/xiaomi/spes/* vendor_xiaomi_spes/ && cd vendor_xiaomi_spes/ && git add . && git commit -s -m "spes: Update blobs"
```
