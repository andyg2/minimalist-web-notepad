# Minimalist Local Notepad

This is a serverless, single-file adaptation of the original [Minimalist Web Notepad](https://github.com/andyg2/minimalist-web-notepad). It has been re-engineered to be a completely private, browser-based notepad that requires no web server or internet connection to function.

## Your Data Stays With You

The most important feature of this notepad is **privacy**.

* **100% Client-Side:** The application is a single `index.html` file that runs entirely in your web browser. There is no backend server.
* **No Data Transmission:** Your notes are **never** sent over the internet. All content is saved directly into your browser's `localStorage`.
* **Persistent & Private:** Your data remains on your computer within the specific browser you used. It is not accessible to other websites, other browsers on your machine, or anyone else.

## How to Use

Getting started is incredibly simple:

1. Download the `index.html` file.
2. Open it in any modern web browser (like Chrome, Firefox, Safari, or Edge).

That's it. You can bookmark the local file path for easy access. Your notes will be saved and will reappear the next time you open the file.

## Features

This notepad provides a simple yet powerful tabbed interface for managing multiple notes.

* **Tab Management:**
  * Click the **+** button on the top-left to create a new note with a unique name.
  * Click on any tab to instantly switch between your notes.
  * The active tab is highlighted in crimson for easy identification.

* **In-Place Renaming:**
  * **Double-click** any tab's name to edit it directly.
  * Press `Enter` or click away to save the new name.
  * Press `Esc` to cancel the edit.

* **Safe Deletion:**
  * Click the small `×` on the right side of any tab.
  * A confirmation dialog will appear to prevent accidental deletion.

* **Automatic Saving:**
  * There is no "Save" button. All changes are saved automatically to your browser's storage a moment after you stop typing.

* **Responsive Design:**
  * The interface supports both light and dark modes based on your system's preference.
  * The tab bar will wrap to multiple lines if you have too many tabs to fit in a single row.

## Copyright and license

This project is a derivative work. The original copyright and license are preserved below.

Copyright 2012 Pere Orga <pere@orga.cat>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License at:

   <http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
