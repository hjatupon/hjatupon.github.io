# hjatupon.github.io

Developer website for my iOS apps, and the host for `app-ads.txt`.

`app-ads.txt` is the file Google AdMob crawls to verify that the AdMob publisher account and
the App Store listings belong to the same person. Until it resolves, AdMob applies **limited
ad serving** to the apps.

For it to work, three things must agree:

1. This file is served at the **root** of the domain — `https://hjatupon.github.io/app-ads.txt`
2. The domain is set as the **Marketing URL** on the App Store listing, exactly as written here
3. The publisher id in the file matches the AdMob account (`pub-5786438340979869`)

Both apps share one publisher id, so this single file covers the whole account.

**Do not delete or rename `app-ads.txt`.** Removing it silently reinstates limited ad serving.
