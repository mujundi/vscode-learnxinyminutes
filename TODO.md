# TODO

- [x] fix: Add webview content persistence on restart/reload using a serializer
- [ ] feat: Command for manually opening cheatsheets

### BACKLOG

- [ ] Add configuration for whether the cheat sheet opens as side view, new tab, or new window. 
- [ ] Write tests for HTML content generation
- [ ] Add localization across the extension
- [ ] Support guides written in non-english languages

### TASKS

## DONE

### Release 0.2.0

- [x] feat: Add configuration for custom cheatsheet associations for each languageId
- [x] feat: Overwrite default assocations with custom assocations from config
- [x] feat: Add command that sets custom file assocation
  - [x] fix: Webview page header displays languageId, not cheatsheet language
### Release 0.1.0

- [x] Create script for converting all markdown files into GFM in HTML form
- [x] Create map for managing languageIds and corresponding cheatsheets
- [x] Write README
- [x] Template Cleanup
  - [x] Command names
  - [x] Remove guide comments
  - [x] Remove console logs
  - [x] Remove quickstart guide
  - [x] Remove unused npm packages
