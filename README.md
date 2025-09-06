## HomeScreen – Your Customizable New Tab Experience

**HomeScreen** transforms your new tab into a personal command center. Built with HTML5, CSS3, and modern JavaScript (ES6+), this powerful tool offers an intuitive bookmark manager, integrated to-do list, robust search capabilities, and extensive customization—all while keeping your data private.

---

### Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
  - [Bookmark Management](#bookmark-management)
  - [Search & Filters](#search--filters)
  - [To-Do List](#to-do-list)
  - [Customization & Settings](#customization--settings)
- [How to Use HomeScreen](#how-to-use-homescreen)
  - [Getting Started](#getting-started)
  - [Bookmark Management](#bookmark-management-1)
  - [To-Do List](#to-do-list-1)
  - [Folder and Settings Management](#folder-and-settings-management)
- [Installation](#installation)
  - [Installing the Latest Version](#installing-the-latest-version)
  - [Installing the Legacy Version](#installing-the-legacy-version)
- [Changelog](#changelog)
- [Useful Links](#useful-links)

---

## Overview

HomeScreen is designed to enhance your online experience by combining:

- **Advanced Bookmark Manager:** Organize and quickly access your websites.
- **Integrated To-Do List:** Keep track of your tasks directly from your new tab.
- **Dynamic Search & Filters:** Find bookmarks by label or URL and filter by status.
- **Customizable Dashboard:** Personalize your background, layout, and interface.
- **Privacy-Focused:** All data remains local unless you decide to export it.

---

## Key Features

### Bookmark Management

- Add, edit, delete, and rearrange bookmarks via drag-and-drop.
- Organize bookmarks in intuitive folders and pin your favorites.
- Automatic favicon fetching with fallback icon generation.

### Search & Filters

- Integrated search scans bookmark labels and URLs.
- Quick filter buttons for starred, unstarred, unread, or read items.

### To-Do List

- Add tasks and manage them with clear buttons for adding, deleting, or restoring.
- Sidebar integration for seamless task management.

### Customization & Settings

- Adjust theme colors, text sizes, layout margins, and bookmark sizes.
- Toggle features like URL tooltips, open-in-new-tab, and display options.
- Export/Import bookmarks and data (supports JSON, with CSV/HTML support coming soon).

---

## How to Use HomeScreen

### Getting Started

1. **Open a New Tab:**  
   HomeScreen launches automatically when you open a new tab.

2. **Initial Setup:**  
   - Familiarize yourself with the interface, including the bookmark input area, to-do list sidebar, and navigation options.
   - Click the settings (⚙️) button to explore customization options.

### Bookmark Management

- **Adding Bookmarks:**  
  Enter a label and URL in the bookmark input fields and click **Add**.
  
- **Editing/Deleting:**  
  Each bookmark card features **Edit** and **Delete** buttons for quick modifications.

- **Organizing with Folders:**  
  - Click the **Folders 📁** button to manage your folders.
  - Create new folders, search among existing ones, and pin your favorites for easy access.

- **Quick Search & Filters:**  
  Use the search bar to filter bookmarks by label or URL.  
  Apply filter buttons (⭐, ☆, 👁️, 📚) to view specific sets of bookmarks.

### To-Do List

- **Managing Tasks:**  
  - Add a new task using the input field in the sidebar.
  - Use the **➕** button to add, **🗑️** to clear, and **⭯** to restore your tasks.
  - Drag and drop to reorder tasks for better prioritization.

### Folder and Settings Management

- **Folder Modal:**  
  - Access the folder modal via the **Folders 📁** button.
  - Search for folders, pin/unpin them, and add new folders by entering a name and clicking **Add Folder**.

- **Settings Modal:**  
  - Open settings by clicking the ⚙️ button.
  - Two tabs are available: **Appearance & Layout** and **Backup & Data**.
  - Customize your theme color, text size, background options, content margins, and bookmark sizes.
  - Manage export/import options for bookmarks and clear all data if needed.

---

## Installation

### Installing the Latest Version

- **For Chrome Users:**
  - Install via the [Chrome Web Store](https://chromewebstore.google.com/detail/new-tab-page-custom-home/dmdeigebfbjbndnnaheobifpfnkhlgbo).

- **For Firefox Users:**
  - Install via [Firefox Add-Ons](https://addons.mozilla.org/en-US/firefox/addon/homepage-new-tab-page/).

### Installing the Legacy Version

- **Legacy Version (simpler UI without folder structure, supports Kiwi Browser):**
  - Install via the [Chrome Web Store - Legacy Version](https://chromewebstore.google.com/detail/new-tab-page-home-screen/dmdeigebfbjbndnnaheobifpfnkhlgbo).

---

## Changelog

### v0.4.8.3
- **Added:**
  - Folder badge on bookmarks in search results and All Folders view (below URL), clickable to navigate to the folder, with tooltip and theme-aware styling.
- **Improved:**
  - Improved hover effect.

### v0.4.8.2
- **Improved:**
  - Updated folder modal design and layout.
  - Refined text truncation logic for to-do items.
  - Set default content margin to 64px.
  - Minor spacing adjustments for to-do list.
- **Changed:**
  - Removed unused comments and general code cleanup.

### v0.4.8.1
- **Improved:**
  - Consistent hover effect and gap for buttons.
  - Settings UI improvements.
  - To-do list UI improvements.
  - Small styling changes.

### v0.4.8
- **Added:**
  - Light mode and dark mode support.
  - Remove completed button to to-do list.
  - Modals in place of browser prompts.
- **Improved:**
  - To-do list dragging.
  - Pinned folder styles.
  - Reworked clearing all bookmarks and folders.
  - Small styling changes.

### v0.4.7.8
- **Added:**
  - Bookmark size limit.
- **Fixed:**
  - Pinned folders buttons react to folder selection correctly.

### v0.4.7.7
- **Added:**
  - New Folder Management window with multiple new ways to explore your bookmarks.
  - Multiple new settings to further customize new folder window and to-do list.
- **Improved:**
  - To-do list elements display.
  - Scrollbar adjustments.
- **Fixed:**
  - Scrollbar fixes.

### v0.4.7.6
- **Added:**
  - Extra safety checks for tooltips to prevent crashes.
- **Improved:**
  - Tooltips now work more reliably across all browsers.
  - Smoother tooltip experience.
- **Fixed:**
  - Fixed tooltips freezing.
  - Scrollbar color fix.

### v0.4.7.5
- **Improved:**
  - Caching mechanism rework for favicons.
  - To-do list UI.
- **Fixed:**
  - Reset filter fix.

### v0.4.7.4
- **Added:**
  - UI improvements: now HomeScreen displays on single view.
  - To-do list toggle button next to Folders button.
  - Tooltips to inform users about functionalities.
  - Scrollbar with back to the top button.
- **Improved:**
  - Event delegation management system and reduced memory usage.
  - Modal display and various other small tweaks.
  - Search debounce.
- **Fixed:**
  - Move selected bookmark fix.
  - Bookmark card hyphenization issue.
  - Various other small fixes and removed unused code.

### v0.4.6.17
- **Added:**
  - Gradient border for to-do list header text with toggle option in Extra settings.
  - Editable to-do list header text with configurable option in settings.
  - Visual feedback when editing headers.

### v0.4.6.15
- **Added:**
  - Option to adjust folder highlighting.

### v0.4.6.14
- **Added:**
  - Current folder highlighting.
- **Improved:**
  - Pinned folders UI.

### v0.4.6.13
- **Improved:**
  - To-do list restore logic.

### v0.4.6.12
- **Added:**
  - To-do list item edit option.
  - Drag handle for to-do list item.
- **Improved:**
  - To-do list drag and drop.

### v0.4.6.11
- **Improved:**
  - To-do list panel CSS improvements.

### v0.4.6.10
- **Added:**
  - Option to save settings when 'x' is clicked in settings panel.
- **Improved:**
  - Settings panel now has three tabs and border.
- **Fixed:**
  - Immediate saving of some settings replaced with a validation step.

### v0.4.6.8
- **Added:**
  - Auto scaling for multiple screens as the default for the bookmark grid.
  - Option in Settings to hide the Move button.
- **Improved:**
  - Move button appears/hidden dynamically when needed and preserves filter state, so bookmarks filtered in search mode remain selected when moving.
  - Settings button positioning has been corrected.
  - Enhanced hover effect over the current folder.
  - Search logic more consistent with filters.
- **Fixed:**
  - Custom background upload functionality.
  - Hiding URL setting now consistently hides bookmark URLs.
  - Drag-and-drop functionality disabled in search.

### v0.4.6
- **Added:**
  - Ability to bulk select and move bookmarks between folders, with a modal interface for moving bookmarks.
- **Improved:**
  - Drag-and-drop functionality for reordering bookmarks and folders with real-time visual feedback.
- **Fixed:**
  - Resolved various UI glitches related to drag-and-drop operations and folder rendering.

### v0.4.5.1
- **Fixed:**
  - Resolved bookmark editing issue in search mode by passing full bookmark objects.
  - Fixed deletion in search mode to retain search results after removal.
- **Improved:**
  - Enhanced search result consistency post-edit or deletion.

### v0.4.5
- **Added:**
  - Export/Import support for bookmarks to/from Chrome/Firefox/other browser HTML export files.
- **Improved:**
  - Updated instructions and UI for bookmark export/import.
  - Minor UI enhancements.

### v0.4.4.2
- **Added:**
  - Settings modal with organized tabs.
  - Toggle for URL tooltip.
- **Improved:**
  - Enhanced favicon fetching with secure methods and improved fallback.
  - Standardized export file format and added notifications.

### v0.4.3
- **Added:**
  - Filters logic with dedicated buttons.
  - Combined filters and search functionality.
- **Fixed:**
  - Bookmark jumping issue during indicator toggling.

### v0.4.2
- **Added:**
  - Improved search scanning both bookmark labels and URLs.
  - "Pin All" and "Unpin All" buttons for folder management.
  - New folder addition via the Enter key.
  - Bookmark indicators for read/starred status (configurable via settings).
- **Fixed:**
  - Minor bug fixes.

### Earlier Versions
- **v0.4.1:** Folder search jumper for folder names.
- **v0.4.0.1:** Added file checker and background format info.
- **v0.4:** Introduced margin settings, updated folder and settings modals, text color customization, and multiple bug fixes.
- **v0.3.x:** Various UI enhancements including button color adjustments, draggable folder buttons, and sidebar width changes.
- **v0.3:** Initial release.

---

## Useful Links

- **GitHub Repository:** [HomeScreenPublic](https://github.com/Pandekte/HomeScreenPublic) – Report issues or send messages.
- **Landing Page:** [HomeScreen Landing](https://pandekte.github.io/HomeScreenLanding/)
- **Chrome Web Store (Latest Version):** [Add to Chrome](https://chromewebstore.google.com/detail/new-tab-page-custom-home/dmdeigebfbjbndnnaheobifpfnkhlgbo)
- **Firefox Add-Ons:** [Install for Firefox](https://addons.mozilla.org/en-US/firefox/addon/homepage-new-tab-page/)
- **Chrome Web Store (Legacy Version):** [Legacy Version](https://chromewebstore.google.com/detail/new-tab-page-home-screen/dmdeigebfbjbndnnaheobifpfnkhlgbo)
