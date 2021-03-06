# Changelist

## Version 3.2
* Feature: Added Base 2nd Edition and Intrigue 2nd Edition.
* Feature: Added Sauno/Avanto Promo Card.
* Feature: Switched to an updated Resw code generator to allow modifying the culture of resources for UWP.
* Cleanup: Updated About pages to point to veleek.com.
* Bug: Clicking a favorite set caused a crash.
* Bug: Unable to open favorites context menu from.
* Bug: After searching on card lookup page, card info links stopped working.

## Version 3.1
* Feature: Added swiping back into UWP version.
* Cleanup: Cleaned up layout on main page.
* Bug: Fixed changelist on about page.
* Bug: Fixed crashing bug on settings page.
* Bug: Fixed loading files from correct paths.

## Version 3.0
* Converted to UWP.
* Added support for Empires.
* Fixed up a bunch of localization.

## Version 2.4
* Updated German and Dutch card names.
* Fixed localization of Set names in most places.
* Update BlackMarket to filter out a bunch of the cards that aren't valid.
* Swiping to replace a card doesn't resort the list.

## Version 2.3
* Added Dominion Strategy Wiki link to Card Info page for a given card
* Added support for 'pinning' a set so that it is always included in the result.
* Updated Picker Result group so that all the cards in result have a 'reason' which indicates why they were included.  This allows the cards to be better grouped in output.
* Updated localization framework to make it much easier to localize complex stuff like 'reason' headers and removed a bunch of redundant code.
* Moved rules that don't usually change (like Platinum/Colony and Shelters) into the settings page and improved the UI to provide a description of the differences.
* Fixed set generation so that minimum cards per set option does not force a minimum number of sets (i.e. Min Cards Per Set = 5 always forced 2 sets).
* Added Events selection options.

## Version 2.2
* Added support for Adventures
* Rules PDFs are now downloaded and cached locally
* Added tags on additional cards in output to see why they are selected.
* Bug fixes for various additional cards not getting added (e.g. Curses)

## Version 2.0
* Switching to two digit versions so that published version will be the same as actually assembly version in app.
* Push to version 2.0 to resolve issue with app not appearing in app list.
* Added Google Analytics.
* Fixed localization stuff for all other languages.
* Fixed localized card names on Black Market page.
* Fixed localized sort orders.

## Version 1.9.3 Change Notes:
* Removed support for localization because app was revoked from marketplace because not the entire application was localized.  The language of various portions of the UI and the cards can still be localized from the settings menu. 

## Version 1.9.2 Change Notes:
* Updated for Windows Phone 8
* Added localization support including most cards Czech, Dutch, Finnish (Suomi), French, German, Italian, Polish, Spanish.
* Added Black Market Deck.
* Added Prince promo card.
* Lots of background updates.

## Version 1.9.3
* Removed support for localization based on phone region because app was revoked from marketplace because not the entire application was localized.  
* The language of various portions of the UI and the cards can still be localized from the settings menu.

## Version 1.9.2
* Updated to Windows Phone 8
* Added localization support including most cards Czech, Dutch, Finnish (Suomi), French, German, Italian, Polish, Spanish.
* Added Black Market Deck
* Added Prince promo card
* Lots of background updates 

## Version 1.8.1
* Old favorites and sets are properly imported into the new model

## Version 1.8
* Added Guilds Expansion
* Switched to new view model to make saved settings files smaller
* Added the ability to show additional required mats and tokens
* Added links to rules documents links in help

## Version 1.7
* Minor bug fixes to picker logic
* Added search box filtering and card details lookup in card filter
* Cleaned up alignment of stuff on the main page and card filter page
* Switched results view to use fonts that more closely match the actual card fonts
* Replaced set short names in results list with set icons
* Cleaned up card info view and made long titles scrollable

## Version 1.6
* Added support for Dark Ages cards
* Added the ability to filter out specific cards completely
* Cleaned up some redundant filter options now (filter specific card types mostly); this can be done with the filter page now
* Result sets show which additional cards are required (colony, madman, spoils, etc.)
* Updating Card Info page to show set icon and cost

## Version 1.5
* Fixed some issues with fast app-switching stuff causing UI to get out of sync with actual settings
* Launching app returns you to the same pivot you were on when exiting (i.e. stays on favorites if you used it last)

## Version 1.4
* Added support for Hinterlands and new Promo Cards
* Added filter for cards with potions in the cost
* Added the ability to save favorite result sets
* Added the ability to edit/rename/delete favorites (including 'factory' reset)
* Prepopulated favorites list with some settings and card sets from rules
* Clicking on a favorite will generate a set using those settings
* Cleaned up layout for options with lists
* Replaced all the progress bars with system tray progress bars

## Version 1.3
* Fixed an issue with filter card options being inclusive instead of exclusive
* Cleaned up results view
* Added potion symbol to card cost in results

## Version 1.2
* Trimmed results to fit on a single page
* Added support for Cornucopia
* Minor bug fixes

## Version 1.1
* Minor update to remove paid version, switched to free version only

## Version 1.0
* Initial Release
* Support for Base, Intrigue, Alchemy, Seaside, Prosperity and all Promo Cards

