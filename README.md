## Local Manifest for syncing Galaxian Dependencies

#### Contains:
<ul>
  <li>device/nothing/Galaxian ← Device Tree</li>
  <li>device/nothing/Galaxian-kernel ← Prebuilt kernel (A16, MT6878)</li>
  <li>vendor/nothing/Galaxian ← Nothing firmware and libraries</li>
  <li>hardware/mediatek ← Common MediaTek hardware stuff</li>
  <li>device/mediatek/sepolicy_vndr ← MediaTek's Vendor SEPolicy</li>
  <li>vendor/sony/dolby ← Dolby Atmos audio panel</li>
</ul>

### Include in `repo sync` sources one-liner:
cd to your build root and paste: <br><br>
`mkdir -p .repo/local_manifests && curl https://raw.githubusercontent.com/Andreyka445/local_manifest/refs/head/main/local_manifest.xml -o .repo/local_manifests/local_manifest.xml`
<br><br>
or, if `curl` isn't installed on your system:
<br><br>
`mkdir -p .repo/local_manifests && wget https://raw.githubusercontent.com/Andreyka445/local_manifest/refs/head/main/local_manifest.xml -O .repo/local_manifests/local_manifest.xml`
