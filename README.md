# Birim Private Files for Claude

Share protected files from your WordPress site by asking Claude: "send the signed Acme contract to jane@acme.com for 7 days, 3 downloads".

## What you need on your site

1. WordPress 6.9 or later.
2. [Birim Private Files](https://birimone.pages.dev/private-files/) and Birim Private Files Pro.
3. The [MCP Adapter](https://github.com/WordPress/mcp-adapter) plugin.
4. An OAuth sign-in plugin for MCP, for example Enable Abilities for MCP. Turn its OAuth server on and copy the connector address it shows.

## Install

In Claude Code:

```
/plugin install birim-private-files --marketplace melihbirim/birim-private-files-claude
```

Enter your site's connector address when asked, and approve the connection on your site the first time Claude uses it.

## License

GPL-2.0-or-later, the same as the WordPress plugins.

## What Claude can do

Find files, create share links (with an email code for the recipient, expiry and download limit), email them from your site, list and turn off links, and read the download log. It acts as the WordPress user who approved the connection, with that user's permissions. Links created by AI must use an email code unless you change that in Media > Share links > Settings.
