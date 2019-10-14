This repository contains up-to-date files downloaded by [bauh](https://github.com/vinifmor/bauh) during runtime.

### Folder and files

#### appimage ( folder )
- It contains the AppImage database files **apps.db** and **releases.db**. These files are updated hourly and are currently
based on the database file provided by https://appimage.github.io.
- These database files are automatically generated by a script.
- The file **no_appimage.txt** contains the names of applications listed in https://appimage.github.io that have no AppImage releases in their GitHub pages. **bauh** does not use it.
It is only used as a source of information.
- The file **no_github.txt** fits in the same case as **no_appimage.txt**, but related to applications with no GitHub repository provided.

#### aur ( folder )
- It contains a file ( categories.txt ) mapping some AUR package names to some categories. Currently this file is manually updated.
- If you want to contribute to categorize some of your AUR packages, send and e-mail to **bauh4linux@gmail.com** listing them in the following format:
```name=category1[,category2,category3,...]```

#### snap ( folder )
- It contains a file ( categories.txt ) mapping some Snap application names to some categories. This file is automatically generated by a script.
