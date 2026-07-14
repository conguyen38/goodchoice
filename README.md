# Good Choice extension pages

This folder is the publishing source for `https://conguyen38.github.io/goodchoice/`.

## Current structure

```text
/
├── index.html
└── seo-lens/
    └── privacy/
        └── index.html
```

- `/index.html` is the public product directory.
- Each extension has its own slug folder.
- Each privacy policy lives at `/<extension-slug>/privacy/index.html`.

## Add another extension

1. Copy the `seo-lens` folder.
2. Rename the copied folder to a lowercase URL slug, for example `image-helper`.
3. Update the copied privacy policy with the new extension name, permissions, data handling, effective date, and support contact.
4. Add a product card and link to the root `index.html`.
5. Push all changes to the branch configured for GitHub Pages.

Example URL:

```text
https://conguyen38.github.io/goodchoice/image-helper/privacy/
```

Use that exact public HTTPS URL in the extension store's Privacy Policy URL field.

## Important

- Do not reuse SEO Lens privacy statements for an extension with different permissions or data practices.
- Keep existing policy URLs stable after an extension is published.
- Test every policy URL in a private browser window before submitting it to a store.
- Update both the policy and the store disclosures whenever data practices materially change.
