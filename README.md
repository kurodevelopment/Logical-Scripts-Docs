# Logical Scripts Documentation

Ready-to-deploy Mintlify documentation starter for Logical Scripts.

## Preview locally

1. Install Node.js 20 or newer.
2. Open a terminal inside this folder.
3. Install the Mintlify CLI:

   ```bash
   npm i -g mint
   ```

4. Start the local preview:

   ```bash
   mint dev
   ```

## Deploy

1. Create a new GitHub repository.
2. Upload everything **inside** this folder to the repository root.
3. Connect that repository in your Mintlify dashboard.
4. Add `docs.logicalscripts.net` as the custom domain in Mintlify.
5. Add the DNS record Mintlify gives you to your domain provider.

## Before going live

- Replace `https://logicalscripts.net` in `docs.json` with your actual Tebex/store URL.
- Replace `https://discord.gg/logicalscripts` with your actual Discord invite.
- Replace the included starter SVG logo files with your real logo if desired. Keep the same filenames to avoid changing `docs.json`.
- Replace example configuration and export names with the exact values used by each released resource.

## Editing pages

Every documentation page is an `.mdx` file. Change its frontmatter title and description, then edit the Markdown beneath it. Add any new page path to `docs.json` so it appears in the sidebar.
