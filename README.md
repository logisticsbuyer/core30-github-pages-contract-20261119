# GitHub Pages site

This package is a dependency-free static site. It does not require a build command.

1. Put every file at the root of a GitHub repository's default branch.
2. In **Settings → Pages**, choose **Deploy from a branch**.
3. Select the default branch and the **/(root)** folder, then save.
4. Edit the HTML, CSS, and assets in GitHub or locally and push changes.

Preview locally with `python3 -m http.server 8080`, then open `http://localhost:8080/`.

Relative asset and navigation URLs allow the same files to work at both `https://owner.github.io/` and `https://owner.github.io/repository/`.
