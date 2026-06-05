# UAP Extra Payouts

Local plugin archive has been built on the workstation:

```text
/Users/macbook/Sites/leo/web86-uap-stripe-global-payouts.zip
```

The workstation currently cannot push to GitHub because neither HTTPS credentials nor an SSH key are configured for `github.com`.

Fastest upload options:

1. Open this repository in GitHub and drag `web86-uap-stripe-global-payouts.zip` into the file upload screen.
2. Configure SSH or HTTPS token locally, then run from `wp-content/plugins/web86-uap-stripe-global-payouts`:

```bash
git push --force-with-lease -u origin main
```

Local source commit used to build the archive: `c3e5090`.
