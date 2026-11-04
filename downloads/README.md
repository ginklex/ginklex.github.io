# Adding downloads

1. Copy the files you want to share into this downloads folder in your local GitHub repository.
2. Edit files.json to list the files. Start with this example, replacing the values with your real filename and description:

```json
[
  {
    "name": "My file",
    "file": "my-file.zip",
    "description": "A short description of this download."
  }
]
```

For more files, add more objects separated by commas. The last object must not have a trailing comma. Filenames are case sensitive. For files in subfolders use a relative path such as guides/instructions.pdf. Do not include downloads/ in the file value.

3. In GitHub Desktop, commit the homepage, files.json, and your files, then click Push origin.
4. Wait for the GitHub Pages deployment and refresh the site.

To remove a listing, remove its object from files.json. To remove access to a published file, also delete the file and push that deletion.

The homepage access code is a casual gate only. Files in this public repository and direct download URLs are public. Do not upload private files or credentials.

Installation: copy index.html and the downloads folder into your repository root. Keep your existing play.html and emulator folder. If you already have a downloads/files.json, merge the entries instead of replacing it with the empty list.
