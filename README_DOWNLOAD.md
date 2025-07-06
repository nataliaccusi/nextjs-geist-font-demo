# How to Download the Juridia App Project as ZIP

To create a ZIP archive of the Juridia app project, you can run the following command in your terminal from the root of the project directory:

```bash
zip -r juridia-app.zip . -x "node_modules/*" -x ".git/*" -x "dist/*" -x "*.zip"
```

This command will create a file named `juridia-app.zip` containing all project files except the `node_modules`, `.git` folder, `dist` folder, and any existing ZIP files.

You can then download or share this ZIP file as needed.

---

If you are on Windows and do not have `zip` installed, you can use tools like 7-Zip or WinRAR to create the ZIP archive manually.

---

Let me know if you want me to create a script or automate this process further.
