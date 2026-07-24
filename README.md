# Brand Logo

Static hosting for the brand logo via GitHub Pages.

## GitHub Pages

1. Open the repository on GitHub → **Settings** → **Pages**.
2. Under **Build and deployment** → **Source**, choose **GitHub Actions** (not “Deploy from a branch”).
3. Push to `main` (or run the **Deploy GitHub Pages** workflow manually under the **Actions** tab). After a successful run, the site URL appears on the workflow summary and under **Settings** → **Pages**.

### Direct image URL

Once deployed, the logo is available at:

```text
https://<organization-or-user>.github.io/<repository-name>/logo.png
```

For this repository (when published under the current remote owner):

```text
https://godrules500.github.io/brand-logo/logo.png
```

### Verify public access

Open that URL in an **incognito / private** browser window while **logged out** of GitHub. The image should load without signing in. If it does not, third-party apps will not be able to fetch it either.

### Private repositories

The repository may remain private only if the organization’s GitHub plan and policies allow GitHub Pages deployment from private repositories. Even then, the **published Pages site itself must be publicly accessible** for an unauthenticated third-party application to load the logo.
