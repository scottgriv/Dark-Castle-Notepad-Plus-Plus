### [Notepad++](https://notepad-plus-plus.org/)

#### Install using Git

If you are a git user, you can install the theme and keep it up to date by cloning the repo:

```bash
git clone https://github.com/scottgriv/Dark-Castle-Notepad-Plus-Plus.git
```

#### Install Manually

- Download using the [Dark Castle.xml](https://raw.githubusercontent.com/scottgriv/Dark-Castle-Notepad-Plus-Plus/main/Dark%20Castle.xml) link or...
- Download using the [GitHub .zip download](https://github.com/scottgriv/Dark-Castle-Notepad-Plus-Plus/archive/main.zip) option and unzip them.

#### Activating the Theme

1. Go to `%AppData%\Notepad++\themes` in windows explorer (%AppData% is platform dependent environment variable. Open a Command Prompt and execute `echo %AppData%`)
2. Place [`Dark Castle.xml`](https://raw.githubusercontent.com/scottgriv/Dark-Castle-Notepad-Plus-Plus/main/Dark%20Castle.xml) inside that folder
3. Restart Notepad++
4. **Dark Castle** will be available in `Settings > Style Configurator`

#### Installing User Defined Languages (Optional)

- Not all languages are supported by Notepad++ out of the box, so a separate theme/language file is needed to support the language syntax.
- View the supported language files in the [userDefineLang](./userDefineLang/) folder.

1. Go to `%AppData%\Notepad++\userDefineLang` in windows explorer (%AppData% is platform dependent environment variable. Open a Command Prompt and execute `echo %AppData%`)
2. Place the extra supported language `.xml` file you want, located in the [userDefineLang](./userDefineLang/) folder, inside that folder
    - The language is defined in the file name with the extension as well, i.e. `Dark Castle-UDL-Markdown-md.xml` for Markdown (.md) files
3. Restart Notepad++
4. **Dark Castle UDL** will be available in `Language > UDL Name (Dark Castle Theme)`
    - Select your UDL based on the file type you have open