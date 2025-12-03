# CRUD JS

Welcome! This is a simple, beginner-friendly web app that demonstrates CRUD operations (Create, Read, Update, Delete) using plain JavaScript, HTML, and CSS. It’s ideal for anyone exploring how data can be created, listed, edited, and removed in a browser—without heavy frameworks.

## What you can do

- Add new items
- View a list of saved items
- Edit existing items
- Delete items you no longer need
- Keep data between page reloads using LocalStorage (optional)

## Quick start

1. Click the green “Code” button on the repository and download the ZIP, or clone it:
   ```bash
   git clone https://github.com/MohammedBelmekki01/crud-js.git
   ```
2. Open the folder and double-click `index.html` to launch the app in your browser.

Optional: If you prefer a local server, run one in the project folder:
```bash
npx serve .
# or any static server you like
```

## How it works

- The app uses a simple form to add or edit items.
- Your items appear in a list where you can edit or delete them.
- Data can be stored in LocalStorage (so it stays after refresh) or in memory (clears on refresh), depending on configuration.

## Screenshots

- Home/List view: shows all items.
- Form view: add or edit an item.

Note: If screenshots aren’t visible here yet, they’ll be added soon.

## Who is this for?

- Students and beginners learning JavaScript basics
- Anyone wanting a minimal, framework-free example of CRUD in the browser
- Developers who want a starting point to extend into a larger app

## Project structure (simplified)

```
crud-js/
├─ index.html         # main page
├─ styles/
│  └─ style.css       # basic styling
└─ src/
   ├─ app.js          # app logic
   └─ store.js        # data handling (LocalStorage or in-memory)
```

Note: File names may vary slightly; the idea is to keep it simple and readable.

## Common actions

- Create: Fill the form and click “Add”.
- Read: Browse the list of items.
- Update: Click “Edit” next to an item, change the fields, and save.
- Delete: Click “Delete” next to an item and confirm.

## Troubleshooting

- Nothing appears? Try a different browser or open the `index.html` from a local server.
- Data not saving? Check that LocalStorage is enabled in your browser. If disabled, items may not persist after refresh.

## Contributing

Suggestions and improvements are welcome!
- Fork the repo
- Create a branch for your changes
- Open a pull request with a clear description

## License

MIT (or to be confirmed). If you don’t see a LICENSE file yet, please assume personal learning use or request clarification.

## Contact

- Author: Mohammed Belmekki
- Repository: [CRUD JS](https://github.com/MohammedBelmekki01/crud-js)

Thanks for visiting! If this helped you learn, consider starring the repo.
