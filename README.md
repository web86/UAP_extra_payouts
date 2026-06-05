# UAP Extra Payouts

This repository currently contains the plugin archive split into base64 parts because direct local git push is not authenticated on the workstation.

To restore the installable zip after downloading the repository:

```bash
cat archive-parts/web86-uap-stripe-global-payouts.zip.b64.part* | base64 -d > web86-uap-stripe-global-payouts.zip
```

Then upload `web86-uap-stripe-global-payouts.zip` in WordPress Plugins > Add New > Upload Plugin, or unzip it into `wp-content/plugins/`.

Local source commit used to build this archive: `c3e5090`.
