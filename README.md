src/ ├── app/ │ ├── index.tsx │ ├── App.tsx │ └── providers/ │ ├── modules/ │ ├── user/ │ │ ├── components/ # reusable within user module │ │ ├── pages/ │ │ │ └── ProfilePage/ │ │ │ ├── index.tsx │ │ │ └── components/ # specific to the page │ │ ├── hooks/ │ │ ├── services/ │ │ ├── types/ │ │ ├── utils/ │ │ └── index.ts │ ├── article/ │ ├── auth/ │ └── ... │ ├── shared/ │ ├── api/ │ ├── config/ │ ├── hooks/ │ ├── layout/ # Header, Footer, Layout │ ├── ui/ # common UI components │ ├── stylesTheme/ │ └── utils/ │ └── main.tsx

markdown
Copy
Edit
