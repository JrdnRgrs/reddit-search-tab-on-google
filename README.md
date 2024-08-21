# Reddit Search Tab on Google (Customizable)

A userscript that enhances your Google search experience by adding a customizable Reddit search tab. This script allows you to quickly perform a search restricted to Reddit posts or include Reddit as a keyword in your query.

## Features

- **Reddit Tab:** Adds a dedicated Reddit tab to the Google search page.
- **Customizable Search Options:**
  - **Site-specific search:** Automatically appends `site:reddit.com` to your search query.
  - **Keyword search:** Adds the keyword `reddit` to your search query.
  - **Dropdown Options:** Choose between different dropdown settings to customize how the Reddit search tab behaves.
- **Multiple Dropdown Modes:**
  - **Tab Dropdown:** Displays a basic dropdown with search options when the Reddit tab is clicked.
  - **Caret Dropdown:** Displays a dropdown when the caret icon is clicked next to the Reddit tab.
  - **Icon Dropdown:** Allows settings configuration via an icon next to the Reddit tab.

## Downloading the Script

You can download the script from:

* [GreasyFork](https://greasyfork.org/en/scripts/504535-reddit-search-tab-on-google)

**Chrome users:** You'll need a script manager extension like [TamperMonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en) or [GreaseMonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/). Then, go to the download link above and click on 'Install'. Finally, click on 'install' in the new window that will open.

**Firefox users:** You'll need a script manager extension like [TamperMonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/). Then, go to the download link above and click on 'Install'. Finally, click on 'install' in the new window that will open.

**Other browsers:** Look for a script manager extension in your browser's add-ons page. Install TamperMonkey or GreaseMonkey, then follow the download instructions above.

## Customizing the Script

You can customize several aspects of the script directly within the code:

- **`tabOnly`**: Set to `true` if you want only the Reddit tab that adds `site:reddit.com`.
- **`tabDropdown`**: Set to `true` if you want a dropdown with search options displayed when the Reddit tab is clicked.
- **`caretDropdown`**: Set to `true` if you want a dropdown displayed when the caret icon next to the Reddit tab is clicked.
- **`iconDropdown`**: Set to `true` if you want a settings dropdown displayed when the settings icon next to the Reddit tab is clicked.
