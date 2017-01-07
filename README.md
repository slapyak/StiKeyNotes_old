# StiKeyNotes Changelog
All of the changes, both published and unpublished, are contained within this file. 
Please submit any bugs or feature requests to [Developer@StiKeyNotes.com](Developer@StiKeyNotes.com)

## [Unreleased Changes]
### Added
- Added Settings window
  - Full delete of keynotes (instead of simple 'deactivation'; both individually and as a batch action)
  - Ability to transfer keynotes, including revision history between open files, both individually and as batch
  - Toggle the 'import' dialog box to default off. Will require manual click of the ribbon button for each new revit model converted to StiKeyNotes.
- Added a third option to view filter -- "View Used"; allows user to see which notes have been placed in the model.
  
### Removed
- Debug popups for licensing errors.

---

## v 0.0.6 - Licensing Hotfix
### Hotfix
- Corrected licensing server interface error preventing new trial signup.
- Added method allowing export for Revit files located on write-restricted areas of storage (such as /programs/ folder)
- Revised Threading for Revit 2017. App will now wait for licensing server response before proceeding.
- Corrected window display issue for Revit 2017.

---

## v 0.0.3 - Initial public release (open beta)
### Added
- All primary functions within Revit scope are enabled.
- Trial Licenses and individual subscriptions are enabled. 
- Trial period currently set to 60 days for Beta period. Trial likely to be 14-days once released.
- Update check and automatic update are enabled.

### Notable Omissions and bugs
* All known bugs are producing error messages to prevent halt conditions. These will be ironed out as the Beta phase closes.
* The currently included help file is being removed in favor of an one-line only help resource. As user numbers increase, this will allow for a community Wiki to be added to the developer made support documentation.
* Enterprise Licensing (shared/floating) is not yet active.
- User configured settings not yet enabled. Intent is for several application level settings as well as more advanced keynote management to be included in this scope.
- When an update is downloaded & installed, the app may require a manual click to start up. This behavior is intermittent.
