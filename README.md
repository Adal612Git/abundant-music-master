# abundant-music

The purpose of this fork is to refactor abundant-music and enable saving of songs locally, and exporting to more file types.

# Run it

1. Clone repository.
2. Install Node Package Manager: https://www.npmjs.com/
3. From project directory, run 'npm install'
4. Run 'npm start'
5. Navigate to 'localhost:3000' in browser.

If you encounter errors related to `event-stream` or `flatmap-stream` during
`npm install`, remove the `package-lock.json` file and try again with a recent
version of Node (v14 or later). The development server now relies on
`nodemon` 2.x.
