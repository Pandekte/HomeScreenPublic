# HomeScreenPublic
Powerful tool for your online experience. HTML5, CSS3, and JavaScript (ES6+) used. 
Customizable new tab page: Utilizes Web APIs like Drag & Drop and LocalStorage for interactivity and persistence. 
Developed with Babel, tested using Jest, and managed via npm & Git. 
Features: HomeScreen functionalities: Bookmark Manager like, Search, To-Do App, Drag & Drop, Privacy, Export/Import, UI.


## Installation

To **Install Newest version of this extension**:
1. Go to the Chrome Web Store and install extension: https://chromewebstore.google.com/detail/new-tab-page-custom-home/dmdeigebfbjbndnnaheobifpfnkhlgbo

1. Go to the firefox ADD-ONS and install extension: https://addons.mozilla.org/en-US/firefox/addon/homepage-new-tab-page/

To **install Legacy version of this extension**:

1. Go to the chromestore and install extension: https://chromewebstore.google.com/detail/new-tab-page-home-screen/dmdeigebfbjbndnnaheobifpfnkhlgbo

## Landing Page
https://pandekte.github.io/HomeScreenLanding/

## Changelog

### v0.4.5.1
- **Fixed**:
  - Resolved issue with editing bookmarks in search mode by passing full bookmark objects for accurate identification.
  - Resolved issue with deleting bookmarks in search mode to retain the search results after removal.
- **Improved**:
  - Enhanced search result consistency after editing or deleting bookmarks.

### v0.4.5
- **Added**:
  - Support for exporting/importing bookmarks to/from Chrome/Firefox/other browser HTML export files.
  - Uniform styling for import modal buttons.
- **Improved**:
  - Updated instructions and UI for bookmark export/import.

### v0.4.4.2
- **Added**:
  - Settings modal with tabs and clear UI.
  - Toggle for URL tooltip.
- **Improved**:
  - Enhanced favicon fetching: Secure fetching & improved fallback mechanism.
  - Export file format standardization and notification.

### v0.4.3
- **Added**:
  - Filters logic & buttons.
  - Combined filters and search logic.
- **Fixed**:
  - Bookmark jumping while toggling indicators.

### v0.4.2
- **Added**:
  - Enhanced search functionality scanning both bookmark labels and URLs.
  - "Pin All" and "Unpin All" buttons in folder modal.
  - Add new folder with Enter key support.
  - Bookmark indicators (stars/eye/book icons).
  - Indicator visibility control via Settings.

### v0.4.1
- **Added**:
  - Folder search jumper for folder names.

### v0.4.0.1
- **Added**:
  - File checker & background format info.

### v0.4
- **Added**:
  - Margin setting and bookmark settings.
  - Updated folders modal and settings modal.
  - Text color customization.
- **Fixed**:
  - Various bug fixes.
  - Removed window button.
