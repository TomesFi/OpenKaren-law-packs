# OpenKaren law packs

The law packs that the OpenKaren app downloads: the full official text of each law, word for word, one Markdown file per article or section, with an index.

- `packs/<id>/`: one folder per pack (`pack.json`, `index.md` and the law files). The hidden `.descriptions.json` in each folder keeps the index descriptions for the next build.
- `catalog.json`: the list the app reads, with each pack's version, size, SHA-256 and download address.
- Each pack is published as a release named `<id>-<version>`, with the zip `<id>-<version>.zip` as its asset.

The packs are made with `karen-packmaker` from the OpenKaren repository. Licences: see `LICENSE.md`.
