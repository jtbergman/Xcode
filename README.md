# Xcode
Helper files for working in Xcode

## Workflows 
This directory contains Automator workflows to help with GitHub. To add these workflows, download the files and double click them.

<img width="888" alt="image" src="https://user-images.githubusercontent.com/61445278/145499504-98f1cb98-0805-4050-96e8-ef0c5815f667.png">

### Limitations
* If your file is edited but not saved, these workflows will fail.
* `Permalink Workflows` The most recent remote commit is used. This could cause a mismatch with local. 
* `PR Workflows` This actually links to the associated commit. You can find the associated PR from this page.

### Recommendations 
You can add custom shortcuts in `System Preferences > Keyboard > Shortcuts > Services > Text"
* Recommend `⌃ + ⌘ + C` (as in Copy) for `Copy GitHub Permalink`
* Recommend `⌃ + ⌘ + S` (as in Show) for `Show GitHub Permalink`
* Recommend `⌃ + ⌘ + A` (as in Author) for `Show GitHub PR`
