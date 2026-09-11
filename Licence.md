Licence.md

SPDX-License-Identifier: GPL-2.0-only

This repository contains a prebuilt boot.img that includes the Linux kernel. The Linux kernel is licensed under the GNU General Public License version 2 (GPL-2.0-only). By distributing this boot image, the distributor must also provide the corresponding source or a written offer to provide the source in accordance with the terms of GPL v2.

What this file contains
- A short license statement and SPDX identifier for the kernel in this image.

What you must provide (replace placeholders below)
- Link to the full corresponding source tree or tarball (exact git URL + commit):
  https://github.com/yourusername/your-kernel-repo@<commit-hash>

- The kernel build .config used to produce the image: add to config/.config

- If you cannot include full sources here, add a written offer (per GPLv2) or a URL where the source tarball can be downloaded.

Suggested steps for compliance
1. Add the exact upstream source repository + commit hash or upload a source tarball in `source/`.
2. Add the kernel `.config` file to `config/.config`.
3. Publish a RELEASE (tag) with boot.img, boot.img.sha256, and a detached GPG signature `boot.img.sig`.

Contact
- Maintainer: fastenaught-byte (https://github.com/fastenaught-byte)

Full text of GPL v2
- The full GNU GPL v2 text is available at: https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt

(You can replace this file with the full LICENSE text if you prefer.)
