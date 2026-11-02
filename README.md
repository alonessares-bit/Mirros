# MirroS Careers

MirroS recruitment website published as a static GitHub Pages site.

The release contains the purple glass interface, continuous page transitions,
11 complete job descriptions, and the copyable application email
**recruit@mirros.ai**. The proposed 3D tilt concepts are not implemented.

`site.zip` contains only the website's static runtime files and required assets.
The GitHub Actions workflow unpacks that release and deploys it to GitHub Pages.
There is no Next.js application server in this hosting setup.

Office documents, original Word files, historical backups, AI concept previews,
credentials, and local dependencies are excluded. Editable project sources and
source evidence remain in the MirroS workspace.

To update the website, prepare a reviewed replacement of `site.zip` with the
`/Mirros` asset base path, then commit it to `main`. Deployment runs automatically.
