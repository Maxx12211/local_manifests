# local_manifests
Clone the repository to the right path

```bash
git clone https://github.com/Maxx12211/local_manifests -b YALP-snowcone .repo/local_manifests
```
# Before repo sync 
Remove the the following lines in rom manifest that includes following paths 
1. hardware/qcom-caf/msm8996/display
2. hardware/qcom-caf/msm8996/audio
3. hardware/qcom-caf/msm8996/media
4. hardware/qcom-caf/wlan

The location will be .repo/manifests/snippets
