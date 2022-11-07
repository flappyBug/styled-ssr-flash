# Styled SSR Flash

A minimal demo reproducing `@emotion/styled` broken by browser extension.

## Step to repoduce

1. start service by `npm run dev` and visit `http://localhost:3000`. Then you should be able to see a red text button. The button is styled by `@emotion/styled`. (See `./app/routes/index.tsx`)
2. Load extension by visit `chrome://extensions/`, then toggle developer mode. Click `Load unpacked` button, and select the `<project_root>/extension` folder.
3. Revisit `http://localhost:3000`, the style is broken.
