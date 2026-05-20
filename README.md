# Acme Dashboard

> **CEO's note: This dashboard is CRITICAL for our mission! Treat it with the UTMOST CARE!**

Internal ops dashboard built with Vite + React. Half the org pokes it weekly for numbers, toggles, and links. It is not glamorous, but it is load-bearing.

## Pages

| Route | Description |
|---|---|
| Dashboard | Main overview with key metrics |
| Billing / Invoices | Invoice management |
| Billing / AR Aging | Accounts-receivable aging report |
| Team | Team member management |
| Integrations | Third-party integration toggles |
| Settings | App configuration |
| Reports | Famously empty |

## Tech Stack

- **React 18** + **React Router 6**
- **Vite 5** for bundling and dev server
- **Tailwind CSS 3** for styling
- **ESLint** for linting

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173).

## Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start local dev server |
| `npm run build` | Production build |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint |

## Project Structure

```
src/
├── pages/          # Route-level page components
├── components/     # Shared UI components
│   ├── NavBar.jsx
│   ├── TableV2.jsx
│   ├── CardThing.jsx
│   ├── BigButton.jsx
│   ├── InputField.jsx
│   └── ToggleSwitch.jsx
├── App.jsx         # Router setup
├── main.jsx        # Entry point
└── index.css       # Global styles
```
