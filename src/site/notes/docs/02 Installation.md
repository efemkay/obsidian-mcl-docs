---
{"dg-publish":true,"dg-path":"02 Installation.md","permalink":"/02-installation/","title":"Installation","pinned":true,"noteIcon":""}
---


This is actually just a CSS code snippets collection. So it isn't an installation per se, but rather **download and enable** in Obsidian.

### Using Snippet Downloader (recommended)
Snippet Downloader is an Obsidian community plugin by Mara Li. Since I'm planning to update this snippets from time to time, this is the recommended approach as the plugin also provides a way to update/redownload from included repository

1. Install **Obsidian42 - BRAT** plugin and enable it
	- Go to `Settings > Community Plugins` and under **Community plugins** click **Browse** button
	- Search for `Obsidian42 - BRAT`, install it and enable it
2. Add Snippet Downloader plugin via BRAT
	- Open Command Palette (hotkey: `Ctrl/Cmd P`)
	- Search for `Obsidian 42 - BRAT: Plugins: Add a beta plugin for testing` and press `Enter`
	- Enter Snippet Downloader URL into the input box
	   `https://github.com/Lisandra-dev/obsidian-snippet-downloader`
3. Ensure Obsidian snippets folder already created
	- Go to `Settings > Appearance`
	- Under **CSS snippets** section, click on the folder icon on the far right
	   *this will create snippets folder inside your Obsidian vault (if you don't have one yet)*
4. Add MCL snippets (https://github.com/efemkay/obsidian-modular-css-layout) via Snippets Downloader
	- Open Command Palette (hotkey: `Ctrl/Cmd P`)
	- Search for `Snippet Downloader: Adding new snippet` and press `Enter`
	- Enter MCL GitHub URL into the input box
	   `https://github.com/efemkay/obsidian-modular-css-layout`
	- Enable MCL snippets by going back to `Settings > Appearance` and under **CSS snippets** section (where you'll find the MCL snippets already downloaded into your vault)


> [!note] Example on how to install using Snippets Downloader
>
> <iframe width="560" height="315" src="https://www.youtube.com/embed/F9z5spGosDI?si=PL4EwJ9wdMyYHCUh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


> [!note] Snippet Downloader plugin can still be used to install MCL
>
> (Updated 27 Aug 2023) [Lisandra-dev](https://github.com/Lisandra-dev/obsidian-snippet-downloader) Snippet Downloader plugin can still be used to install MCL recently archived the plugin, but it is still very much functional for downloading snippets. There's additional step for you to install the plugin (since it's no longer available via Community Plugins) - it is reflected below...

> [!warning]
> Please ensure your vault's /.obsidian/snippets folder is already created before doing the following steps. You can do that by going to `Settings > Appearance` and click "Open snippets folder" under CSS snippets section

> [!warning]
> For this features to work, please make sure your Obsidian **Installer** version is at v1.1.9 or higher as per screenshot below. Note that in Obsidian the "Current version: v1.x.x" is the App version while "(Installer version: v1.x.x)" is the **Installer** version I'm referring to above.
> 
> ![0b2fa16129e322205240958a971b27325ed39764png 658×160 obsidianmd](https://forum.obsidian.md/uploads/default/original/3X/0/b/0b2fa16129e322205240958a971b27325ed39764.png)

### Manually Saving from GH - Downloading the Zip File
1. **Go to MCL's GitHub Releases page**
	- Open your browser and go to MCL's GitHub Releases page
		- https://github.com/efemkay/obsidian-modular-css-layout/releases
2. **Download the zipped file of MCL Releases page**
	- On MCL GH [releases page](https://github.com/efemkay/obsidian-modular-css-layout/releases), under the latest release and under the "Assets" section, click on the snippets zip file (it's named `MCL-snippets-x.x.x.zip`). This will trigger a download action.
		- *The zip file contains all three snippets*
		- *You should download from the latest release, which would be the top one*
3. **Extract and save the snippets to your Obsidian's `snippet` folder**
	- Open the zip file and extract it to your vault's snippets folder. It should be `[vault]/.obsidian/snippets`
		- *You may delete the zip file*
4. **Enable the snippet(s)**
	- Open Obisidian and go to `Settings > Appearance > CSS snippets` to enable the snippet.
		- *Note that you may have to click on "Reload snippets" button if the snippet does not appear in the list.*


### Manually Saving from GH - Copy Paste from `raw`
1. **Go to MCL's GitHub [landing page](https://github.com/efemkay/obsidian-modular-css-layout)**
	- Open your browser and go to MCL's GH landing page
		- https://github.com/efemkay/obsidian-modular-css-layout
2. **Copy the snippet(s) from the MCL's GH**
	- On GH landing page, click on the snippet you want to save (there's three (3) of them)
	- (on the blob page) click on "Raw" at the top left, and (on the raw page) copy the entire text
		- *Note that GH raw page will open up the css file within your browser in plain-text format for easy copy pasting*
3. **Save the snippet(s) to your Obsidian's `snippet` folder**
	- Open any text editor in your desktop and paste the snippet
	- Save the file as a `.css` file into your `[vault]/.obsidian/snippets` folder. Filename can be anything.
4. **Enable the snippet(s)**
	- Open Obisidian and go to `Settings > Appearance > CSS snippets` to enable the snippet.
		- *Note that you may have to click on "Reload snippets" button if the snippet does not appear in the list.*

---

**< [[docs/01 Docs Home\|MCL Home]] | Next: [[docs/01 Wide Views/01 Wide Views\|Wide Views]] >**