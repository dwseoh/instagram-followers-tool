# instagram-followers-tool

A static HTML web app to read Instagram data export data and stats from an overview. 
Go through a list of people that you follow but don't follow you back, or the people that follow you but you don't follow back.

Everything runs on the browser with no network requests. 

## DIY

Use the deployed link or simply clone the repo, and double-click `index.html` (or drag it into a browser tab).

## Privacy

The export is parsed by JavaScript within the browser. Usernames and swipe progress are stored in that browser's `localStorage` (device-only), and there is an option to clear the data as well. 

## How to export your data from Instagram

Settings → Accounts Center → Your information and permissions → Download your information → Download or transfer information → **Some of your information** → **Followers and following** → Download to device → format **JSON**, range **All time**.

Usually this is a quick process. Then, simply drop the `.zip` in as-is. JSON format is required.