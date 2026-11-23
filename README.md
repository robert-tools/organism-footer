# 🗂️ @robert.tools/organism-footer

Provides a standardized footer.

## 📜 Usage

### 🟢 Installation

```bash
npm install @robert.tools/organism-footer
```

### 📝 Sample usage

#### prerequisites

- define css variables

#### depending filters

- [safeParam](https://github.com/robert-tools/eleventy-filter-safe-param)

#### depending components

- [atom-text](https://github.com/robert-tools/atom-text)
- [molecule-link](https://github.com/robert-tools/molecule-link)

#### Template

Use the footer component as shown below:

```html
{{ component("organism/footer", {
    prefix: "2026 Made By",
    text: "Robert Willemelis",
    css: "text-danger",
    url: "https://robert.berlin"
}) }}
```

##### ⚙️ parameter

- **prefix**: text before a link
- **text**: text within the link, when url defined
- **css**: overwrite css class for the text
- **url**: url of the link

#### CSS

Use the basic styling

```css
@import '@robert.tools/organism-footer/src/index.css';
```

#### TypeScript

Include TypeScript by importing the component

```typescript
import * as OrganismFooter from '@robert.tools/organism-footer';
```

## ⚖️ Notes

This software is hand-crafted, test-driven and assisted by AI tools. I know each
line of my code. ✌️

| Tool | Comment |
| --- | --- |
| ![assisted by Jest](https://img.shields.io/badge/Jest-TDD-008800?logo=jest) | Test-driven development with Jest |
| ![assisted by robert.tools](https://img.shields.io/badge/robert.tools-ecosystem-008800) | Part of the robert.tools ecosystem |
| ![assisted by GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-assisted-8A2BE2?logo=githubcopilot) | Code completion |
| ![assisted by OpenAI](https://img.shields.io/badge/OpenAI-assisted-8A2BE2?logo=openai) | chatGPT research |
