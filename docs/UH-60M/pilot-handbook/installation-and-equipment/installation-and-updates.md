# Installation and Updates

The H-60 is a PC add-on. The installable download on the [aircraft releases page](https://github.com/Delta-Simulations/MSFS-H-60M/releases/latest) is **deltasimulations-uh60.zip**, under **Assets**. GitHub also offers a source archive for each release. That archive contains the project used to build the aircraft. Choose the named aircraft ZIP for your Community folder.

## Find the active Community folder

| Simulator | Where to look |
| --- | --- |
| MSFS 2024 | Open **Marketplace → My Library**, choose **Settings** beside the search field, then **Open**. This opens the active Community folder in File Explorer. |
| MSFS 2020 | Enable **Developer Mode** in the general settings. In the developer toolbar, open **Virtual File System → Packages Folders → Open Community Folder**. |

Opening the folder from the sim is especially useful if you installed packages on another drive or have both simulator versions on the same PC.

## Install the aircraft

1. Note the release tag on GitHub. Download and extract **deltasimulations-uh60.zip**.
2. Open the extracted folder. Find **deltasimulations-uh60** with **manifest.json** and **layout.json** inside.
3. Close MSFS. Copy that package folder to the Community folder you opened above.
4. Check the result in File Explorer. You should be able to open `Community\deltasimulations-uh60\manifest.json` directly. A second **deltasimulations-uh60** folder between those two levels keeps the sim from finding the package.
5. Launch the simulator and look for **UH-60** in the aircraft selector. In MSFS 2024 you can also select the **Community** filter in **My Library** to check whether the sim recognized the package.

## Update an existing installation

With MSFS closed, move the previous H-60 package outside Community before copying the new one in. Keeping a backup elsewhere lets you return to the older build and keeps obsolete files out of the updated aircraft. For the first flight after an update, select one of the included liveries. If it loads correctly, try your usual repaint.

If you use a development build, record its commit or archive date. For a release build, keep the GitHub tag. A report that identifies both the H-60 build and the MSFS version is easier to reproduce.
