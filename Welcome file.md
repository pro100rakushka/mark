# Welcome to MarkHub!
- 1
- 2
- 3
- 4
- 5

*Hiiii*

Hi! I'm your first Markdown file in **MarkHub**. If you want to learn about MarkHub, you can read me. If you want to play with Markdown, you can edit me. If you have finished with me, you can just create new files by opening the **file explorer** on the left corner of the navigation bar.


# Files

MarkHub stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## Create files and folders

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.

## Switch to another file

All your files are listed in the file explorer. You can switch from one to another by clicking a file in the list.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export file to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template.  With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.


# Synchronization

Synchronization is one of the biggest features of MarkHub. It enables you to synchronize any file in your project with other files stored in your **Google Drive** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The project synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your project on any other device.
	> To start syncing your project, just sign in with Google in the menu.

- The file synchronization will keep one file of the project synced with one or multiple files in **Google Drive** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the project, any modification in the file will be automatically synced.

## Save a file

You can save any file of the project to **Google Drive** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the project is already synced, you can save it to another location. MarkHub can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, MarkHub will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Online publishing via the MarkHub platform simplifies this process for your web-book:  you can publish a project by clicking the **Publish now** button in the navigation bar. Every file in a project will be considered as a web-book chapter and displayed in the alphabetical order. The publishing process will require some time based on the content and its complexity. Once publishing is completed, there will be a modal window with a link to the web-book. You can republish your web-book many times to receive a version you are satisfied enough for further sharing. To do that, you can share a web-book's link anywhere.

> Your web-book link will exist for 30 days with no cost.

# Markdown extensions

MarkHub extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **Project properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).
<!--markhub_data:
eyJoaXN0b3J5IjpbLTg5Nzg4ODYwNV19
-->
