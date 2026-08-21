# CodePlusPluss

**CodePlusPluss** is a simple Windows code editor made with C++ and Win32 API.

It started as a small project because I wanted to make my own code editor instead of always using a huge IDE for everything.

Right now, it supports **C, C++, Python and plain text**, with some basic features like syntax highlighting, auto indentation, file management and encoding selection.

It's still a work in progress, so don't expect it to replace VS Code anytime soon. I'm just building it step by step and adding stuff as I go.

---

## Features

* C / C++ editing
* Python editing
* TXT / plain text editing
* Basic syntax highlighting
* Auto indentation
* TAB support
* UTF-8 and ANSI encoding
* Open / Save / Save As
* Language selection
* Simple output panel
* Lightweight Windows UI
* Keyboard shortcuts
* File type detection

---

## Supported Languages

### C

Basic syntax highlighting for common C keywords, strings, numbers, comments and preprocessor lines.

### C++

C++ is currently one of the main languages I'm working with.

It supports basic highlighting for things like:

* Keywords
* Strings
* Numbers
* Comments
* `#include`
* `#define`
* Some common STL-related keywords

### Python

Python files are supported with basic highlighting and automatic indentation.

### Text

And if you just want to write normal text, that works too.

No need to make everything complicated.

---

## Screenshots

Screenshots will be added as the UI changes.

The current interface is intentionally pretty simple: editor on top, output panel at the bottom, and the usual File / Language / Encoding menus.

---

## Download

### Latest Release

**CodePlusPluss 1.1.2**

Download:

**CodePlusPlus-1.1.2.zip**

The ZIP contains the current Windows build and the project files.

---

## How to Use

1. Download the latest ZIP.
2. Extract it somewhere.
3. Open the application from the `app` folder.
4. Create a new file or open an existing one.
5. Start coding.

That's basically it.

No 500-page setup guide required.

---

## Keyboard Shortcuts

| Shortcut   | Action                      |
| ---------- | --------------------------- |
| `Ctrl + N` | New C++ file                |
| `Ctrl + O` | Open file                   |
| `Ctrl + S` | Save                        |
| `Tab`      | Insert indentation          |
| `Enter`    | New line + auto indentation |

More shortcuts may be added later.

---

## Project Structure

```text
CodePlusPluss/
│
├── app/
│   └── CodePlusPluss.exe
│
├── code/
│   └── Source code
│
├── version/
│   └── Version / update notes
│
└── README.md
```

I keep the executable, source code and version information separated because it makes the project a bit easier to manage.

---

## Built With

* **C++**
* **Win32 API**
* **Windows Rich Edit**
* **MinGW / GCC**

No giant framework sitting in the middle.

Just C++, Windows API and a questionable amount of time spent staring at compiler errors.

---

## Why I Made This

Mostly because I wanted to.

I like messing around with programming and Windows stuff, and making a code editor seemed like a pretty good project to learn from.

There's also something kinda fun about making a program that you actually use yourself.

CodePlusPluss isn't trying to be the next VS Code or Visual Studio.

It's just my own editor, and I'm slowly making it better.

---

## Current Version

### CodePlusPluss 1.1.2

Current features include:

* File creation
* File opening
* Save
* Save As
* C / C++ / Python / Text modes
* Basic syntax highlighting
* Auto indentation
* UTF-8 / ANSI
* Output panel
* Native Windows interface

---

## What's Next?

Some stuff I'd like to add eventually:

* Better syntax highlighting
* More languages
* Line numbers
* Find / Replace
* Dark mode
* Better themes
* More keyboard shortcuts
* Compiler integration
* Run code directly from the editor
* Better error messages
* More settings
* General UI improvements

Some of these might happen soon, some might take forever.

Depends on how much time I have and how badly Windows decides to fight me that day.

---

## Development

This project is still actively being worked on.

The code may change quite a lot between versions, so things might break occasionally.

If you find a bug, feel free to open an issue and include:

* CodePlusPluss version
* Windows version
* What you were doing
* What happened
* What you expected to happen
* Any error message you got

Screenshots are also useful.

---

## Feedback

Suggestions are welcome.

If you have an idea for a feature, feel free to open an issue and explain what you'd like to see.

I'm especially interested in ideas that actually make the editor easier to use instead of just adding random buttons everywhere.

---

## Roadmap

The general plan is pretty simple:

**Make it work → make it better → add more stuff → probably break something → fix it → repeat.**

That's basically development.

---

## Status

**CodePlusPluss 1.1.2 — Active Development**

It's not finished, and it's not supposed to be.

I'm still learning, experimenting and adding things to the project.

If you're checking this repository out, thanks for stopping by.

---

## Author

Made by **tuin5995-rgb**.

CodePlusPluss is an independent project built for learning, experimenting and, hopefully, becoming a genuinely useful little code editor.

More updates coming later.

---

**CodePlusPluss**
*Simple code. Simple editor. No unnecessary nonsense.*
