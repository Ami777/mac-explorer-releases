## Changes

## Add experimental rclone cloud disks
- Complete Dropbox, OneDrive, and S3 cloud setup
- Add secure SFTP cloud disks
- Coalesce cloud credential access per session
- Virtualize advanced rclone provider forms
- Prepare rclone Keychain access once per session
- Use the native Settings window title bar
- Make deletion safe across remote volumes
- Add per-disk Google API limits
- Stabilize shared cloud disk mounts
- Detect and recover from cloud connection stalls
- Make cloud shutdown fast and race-safe

## Other 

- fix(stability): prevent selection and volume-check freezes
- feat(cloud): add bundled rclone provider presets
- fix(cloud): secure reauthorization and prevent preview write-back
- fix(cloud): isolate and order transfer monitoring
- fix(cloud): retain and finish transfer activity logs
- feat(cloud): log per-file upload and download activity
- fix(cloud): sync capacity without reloading My Computer
- feat(cloud): make auto-connect a per-disk policy
- fix(computer): align drive grid to three columns
- feat(cloud): add lightweight provider icons across disk views
- feat(cloud): tune modtime policy per backend
