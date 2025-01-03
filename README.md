# Museumgasthof Ochsen Webseite

Die Hauptinformationen können in der index.astro bearbeitet werden. Hier bei immer das Format und Zeichen belassen.
```text
/
├── src/
│   └── pages/
│       └── index.astro
```

Außerdem kann die PDF für die Speisekarte jederzeit ausgetauscht werden. Bitte hier genau an den Namen der Datei halten, also alles in Kleinbuchstaben und PDF Dateiformat.
```text
/
├── public/
│   └── speisekarte.pdf
```

## 🚀 Project Structure

```text
/
├── public/
│   └── images/
│   └── favicon.svg
│   └── speisekarte.pdf
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── datenschutz.astro
│       └── impressum.astro
│       └── kontakt.astro
│       └── speisekarte.astro
│       └── ueber.astro
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
