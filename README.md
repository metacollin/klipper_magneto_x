## Magenta X: Custom Magneto X Firmware

### Why?
- The official Magneto X firmware is based on an ancient verison of Klipper from **May 25, 2023**. This is, frankly, unacceptable for a professional-grade printer like the Magneto X, and means that several critical bugs that have since been fixed upstream (most noteably bugs that mostly break input shaping) are still at large in the official Magneto X firmware and impacting users. This firmware incorporates of Peopoly's Magneto X specific code into a much more recent version of Klipper. Currently tracking Klipper nightly @ **December 26th, 2024**
- Peopoly didn't do a proper fork of klipper and broke all commit history, making it impossible to track upstream changes or make PRs to upstream. This correctly forks upstream Klipper
- To make it easy to incorporate new features/improvements into the Magneto X firmware from upstream

### How?
- Git fu and love.

### When?
- Now, I think
