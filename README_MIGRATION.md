# CUPLIDE / CuplSDK GitHub Pages migration

This folder is ready to publish with GitHub Pages.

## Recommended GitHub Pages layout

If you want a URL similar to Bitbucket Pages, create a GitHub repository named:

```text
TEU_USER.github.io
```

Then publish this folder at the repository root. The final URLs will be:

```text
https://TEU_USER.github.io/
https://TEU_USER.github.io/CuplSDK/
https://TEU_USER.github.io/CuplSDK/update/
https://TEU_USER.github.io/Logisim/version.xml
https://TEU_USER.github.io/p16-simulator/version.xml
```

If you use a project repository, for example `cuplide-update`, the URLs will be:

```text
https://TEU_USER.github.io/cuplide-update/
https://TEU_USER.github.io/cuplide-update/CuplSDK/
https://TEU_USER.github.io/cuplide-update/CuplSDK/update/
```

## What to edit before publishing

Open `CuplSDK/index.html` and replace:

```text
TEU_USER
TEU_REPO
```

with your real GitHub user/organization and repository name.

## Update site p2

Put your Eclipse p2 repository files inside:

```text
CuplSDK/update/
```

Expected files:

```text
content.jar
artifacts.jar
features/
plugins/
```

## Legal note

The file `cupl.msi` appears to be the Atmel CUPL installer. Publish it only if you have permission to redistribute it.
