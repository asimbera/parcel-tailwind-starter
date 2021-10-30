# Parcel Tailwind Starter

Template for a web project equipped with Tailwind CSS.

## Using

- On github :
  Just click on `Use this template` on top of the repo.
- degit :
  `degit asimbera/parcel-tailwind-starter#main my-app`

This repo contains `src/index.html` as an entrypoint. If you like to use another file as entrypoint then update the `source` entry in [package.json](./package.json).

### Additional Notes

If you are trying to deploy the site in github pages from the workflow, then consider adding below code in the project's `package.json` file.

```json
"targets": {
    "default": {
      "publicUrl": "<public_url>"
    }
  },
```

Change the `<public_url>` part with your site's public url or absolute url, like: `https://asimbera.github.com/` or `https://asimbera.github.com/parcel-tailwind-starter` or `/parcel-tailwind-starter`.

**❗ If you dont do this part then you will get 404 errors for any asset of your site.**

## Feedback

If you like any feature to be added or have found any bug then create an issue.
