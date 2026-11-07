# Document portal template

**A free page where people open, fill in and sign your documents. Made from a GitHub template in two minutes.**

Live example: https://sumofficeapp.github.io/document-portal-template/

A free page for your team, school or business where people open your documents, fill them in and sign them in the browser. No server, no code.

## Make your own in two minutes

1. Click **Use this template** above, name the repository, keep it public.
2. Put your `.docx`, `.xlsx` and `.pptx` files into the `documents` folder.
3. Settings → Pages → Deploy from branch `main`, folder `/ (root)`.

Your page is at `https://<your-name>.github.io/<repository>/`. Every file gets an **Open, fill in, sign** button.

Edit `config.json` for the title, the intro line and live documents from the Layers catalog (4,000+ letters, contracts and calculators):

```json
{
  "title": "Harbor Bakery: documents",
  "intro": "Read, fill in and sign our documents right in your browser.",
  "forms": [{ "slug": "invoice-template-with-tax-calculation", "title": "Invoice with tax calculation" }]
}
```

## What people get

The document opens in Layers as a fast page, on a phone too. They fill in their part, send it for signature, save a finished copy. Start free: https://app.layers.md/register?from=door-portal. Plans: https://layers.md/pricing?from=door-portal.

MIT. Made by SumOffice.
