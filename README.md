## Local Manifest for syncing Galaxian dependencies.

#### Contains:
<ul>
  <li>device/nothing/Galaxian ← Device Tree</li>
  <li>device/nothing/Galaxian-kernel ← Prebuilt kernel (A16, MT6878)</li>
  <li>vendor/nothing/Galaxian ← Nothing firmware and libraries</li>
  <li>hardware/mediatek ← Common MediaTek hardware stuff</li>
  <li>device/mediatek/sepolicy_vndr ← MediaTek's Vendor SEPolicy</li>
  <li>vendor/sony/dolby ← Dolby Atmos audio enhancements</li>
</ul>

### `repo` quick setup:
After syncing your ROM's manifest, cd to the root dir and paste: <br><br>
`mkdir -p .repo/local_manifests && curl https://raw.githubusercontent.com/Andreyka445/local_manifest/refs/heads/main/local_manifest.xml -o .repo/local_manifests/local_manifest.xml`
<br><br>
or, if `curl` isn't installed on your system:
<br><br>
`mkdir -p .repo/local_manifests && wget https://raw.githubusercontent.com/Andreyka445/local_manifest/refs/heads/main/local_manifest.xml -O .repo/local_manifests/local_manifest.xml`
