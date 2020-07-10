# Profile Changelog

## v2.3
Release date : 15 Jul 2020

### Improved
* Compatibility with PHP 7.2


## v2.2.1
Release date: 10 Oct 2018

### Improved
* module now is compatible with varchar-type datatype of the module version 

## v2.2
Release date: 15 Sep 2013
Revision: 

### Improved
* Links for profile actions needed in the main template, not just the main menu (#422)
* No option to make a field required for registration (#423)
* Creating and editing the registration steps is very cumbersome (#424)

### Fixed
* Admin breadcrumb displays language constant for several tabs when Main Menu is deactivated (#421)
* module update with error (#436)
* bug for openID (#446)

## v2.1
Release date: 1 Okt 2012
Revision: 

### Improved
* Password encryption methods

## v2.0
Release date: 18 Sept 2011

### Fixed
* (#386): a password change no longer leads to problems when trying to login again (phoenyx)
* (#356): fixed all module preferences (phoenyx)
* (#367): field types date, date and time and longdate can now be created (phoenyx)
* (#273): users can now delete their own account (phoenyx)
* (#429): modified initial field assignments to categories and display permissions (phoenyx)
* (#434): registred users can delete their own audio files now (phoenyx)
* (#435): avatars can now be bigger as the thumb size for pictures (phoenyx)
* (#437): getting the gravatar from an anonymous user being a member of a group no longer results in a fatal error (phoenyx)
* (#439): the assignment of a field to a regstep can now be undone (phoenyx)
* (#441): users can no longer change configs of other users (phoenyx)
* (#441): administrators can now suspend users (phoenyx)
* (#447): validating uname, login_name, email and password whereever it's necessary it is no longer possible to register multiple times with the same email address (phoenyx)
* (#449): multiple visits of the same user on the same profile are now logged correctly (phoenyx)
* (#453): displaying correct usernames in your friends block (phoenyx)
* (#479): missing links in the admin menu are now displayed correctly (phoenyx)
* (#562): list of approvals is now displayed correctly in case the user doesn't have own groups (phoenyx)
* (#703): hide fields based on visibility status (phoenyx)
* (#794): email is now shown as required on registration form (phoenyx)

### Added
* (#272): implemented notifications for pictures, audio, video, group discussions and replies to group discussions (phoenyx)
* (#338): admin menu icons added (phoenyx)
* (#335): user menu block added (phoenyx)
* (#339): groups can now be searched via the core search system (phoenyx)
* (#336): groups can now be merged on acp side (phoenyx)
* (#441): autotask to reactivate suspended users (phoenyx)
* (#334): user information on index.php is now generated dynamically based on the fields and visibility setup (phoenyx)
* (#450): the weight of categories and fields can be modified directly on the overview (phoenyx)
* (#798): added filter to select groups by user on ACP side (phoenyx)

### Improved
* (#376): added category column and category filter to fields administration in the ACP (phoenyx)
* (#405): initial avatar is now linked to the pictures section (phoenyx)
* (#364): complete code review (using icms variables and functions, using IPF in more places, template cleanup). Also covering the userinfo.php page which is now ready to use. review of all language constants. following the refactoring of the core. (phoenyx)
* (#271): corrected some redirects (phoenyx)
* (#440): updated dewplayer to version 1.9.9 (phoenyx)
* (#445): applied naming convention for all language constants (phoenyx)
* (#401): text in header bars is now clickable as well (phoenyx)
* (#162): ongoing process of IPFing the module (phoenyx)
* (#330): renaming tribes into groups, tribeuser into membership (language constants) (phoenyx)
* (#780): improved language constants for identifier field on fields (sato-san)