# Deploy to GitHub Pages

1. **Create the repo on GitHub** (if not yet created): New repository named exactly `catherine-lisa.github.io` (no README/license).

2. **Push from this folder** (terminal needs outbound access; if you use a proxy, run your proxy command first):
   ```bash
   cd "d:/DWF-CODE/githubio/io/yhliu918.github.io"
   # Run your proxy command here if needed, e.g.:
   # export https_proxy=...
   git push -u origin master
   ```

3. **Enable GitHub Pages**: On GitHub → repo **Settings** → **Pages** → Source: **Deploy from branch** → Branch: `master`, folder **/ (root)** → Save.

4. Site will be at **https://catherine-lisa.github.io**.
