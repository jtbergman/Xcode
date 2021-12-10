# Xcode
Helper files for working in Xcode

## Workflows 
This directory contains Automator workflows to help find things in GitHub. 

<img width="888" alt="image" src="https://user-images.githubusercontent.com/61445278/145499504-98f1cb98-0805-4050-96e8-ef0c5815f667.png">

### Limitations
* If your file is edited but not saved, these workflows will fail.
* The most recent remote commit or default branch is used which could cause line mismatches.
* The `Show GitHub PR` workflow links to the associated commit. This page contains a link to the PR. 

### Recommendations 
You can add custom shortcuts in `System Preferences > Keyboard > Shortcuts > Services > Text`
* Recommend `⌃ + ⌘ + C` (as in Copy) for `Copy GitHub Permalink`
* Recommend `⌃ + ⌘ + S` (as in Show) for `Show GitHub Permalink`
* Recommend `⌃ + ⌘ + A` (as in Author) for `Show GitHub PR`
