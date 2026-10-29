Practical 11 needs the Ubuntu Desktop installer image. It is too large to include here (about 6 GB).

Before the practical, the lab technologist should:
1. Download ubuntu-24.04.1-desktop-amd64.iso (or the current 24.04.x point release) and its SHA256SUMS file
   from the official Ubuntu releases page: https://releases.ubuntu.com/24.04/
2. Verify it:  sha256sum -c SHA256SUMS --ignore-missing   (expected output: ...iso: OK)
3. Copy the ISO and SHA256SUMS to ~/ISO on every lab PC image, so students do not download it in class.

If the point release has changed, update the ISO file name in Practical 11 Section D and in the steps.
