# Upcoming

## general

* Fixed an issue with wrong player identity carrying over to main menu.
* Disabled autosaving due related issues.
* Disabled tasks tab being broken and unfinished, you should now be able to ask from characters what they still need.
* Fixed characters triggering special events on second level load (including Rob's tenement upgrade menu) (issue [#172](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/172))
* Fixed special item events not triggering (including sleeping pills, piggybanks and etc...) 

## quests

* Fixed "A path to riches" quest updating state even when quest is not assigned.

## leval

* Fixed inn wc being a death trap. (issue [#160](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/160))
* Fixed shops not openeing when they should.

# 4.12.2018 (0.0.4)

## general

* Added sleeping pill item.
* Added a punishment for stealing.
* Added caffeine effect
* Fixed typos in item names.
* Fixed "landing animation" triggering every time when player is even a little in air (issue [#62](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/62))
* Fixed every load starting discussion with Axel Nordberg (issue [#92](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/92))
* Fixed possibility to skip first dialog with border inspector (issue [#29](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/29))
* Fixed " " being a valid name (issue [#53](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/53))
* Fixed active brewing barrels breaking time upon save game load (issue [#143](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/143))
* Fixed new games breaking when returning to main menu (issue [#121](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/121))
* Fixed unpickable items (issue [#150](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/150))
* Fixed "Equip" not working.
* Now tenants pay rent every day.
* Fixed stats depleting fast after waking up.

## quests

* Added a bottle collecting quest.

## level

* Removed debugging item pile
* Fixed various minor issues.
* Added prison cell.
* Stocked up O-Market (issue [#129](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/129))

# 1.12.2018 (0.0.3)

## general

* Added icons for items missing one.
* Adjusted tenement upgrade prices.
* Adjusted item prices and effects
* Adjusted falldamage (issue [#97](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/97))
* Fixed soundscapes not activating upon loading a save (issue [#93](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/93))
* Fixed second game loading not working (issue [#94](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/94))
* Fixed loadscreen unfading before loading is completed (issue [#91](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/91))
* Fixed ability to steal from vendors by double clicking an item (issue [#109](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/109))
* Saves now carry player rotation (issue [#103](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/103))
* Fixed camera jutter when player runs towards camera (issue [#111](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/111))
* Added autosave when waking up (Still missing from UI).
* Fixed player identity not saving and loading properly (issue [#110](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/110))

## quests

* Added "tutorial" moonshining quest.

## dialogue

* Banker and innkeeper have learned to speak english (issue [#50](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/50))

## main menu

* Fixed a typo (issue [#115](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/115))

## intro

* Added textures for a bus (issue [#14](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/14))

## level

* Fixed collision issues on roads (issue [#101](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/101))
* Fixed locked doors appearing as unlocked (issue [#107](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/107))


# 28.11.2018 quickfix (0.0.2)

* Fixed broken cursor

# 27.11.2018 (0.0.2)

## main menu

* Added controls menu

## general

* Added a few starting items for player
* Added ability to save and load game
* Added an effect when consuming Huribo Evilbear
* Added models for few items.
* Added a clock indicating time when asleep 
* Added a message when player is not tired enough to use a bed. (issue [#49](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/49))
* Giving Ville Sköldganster a whiskey actually gives him a whiskey now (and requires whiskey to exist in player inventory).
* Changed withdrawal symptoms to increase depression instead of damaging player
* Changed pressing escape to close inventory first (issue [#79](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/79))
* Fixed some items being unable to drop
* Fixed some dialog typos.
* Fixed player camera base conversation (issue [#24](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/24))
* Fixed border inspectioner not using player's name(issue [#10](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/10))
* Fixed dialogue UI scaling(issue [#34](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/34))
* Fixed map does not accurately reflect which direction you are facing in first-person mode(issue [#43](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/43))
* Fixed tenement marker vanishing when finding other locations (issue [#61](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/61))
* Fixed item UIs opening to previously visited tab (issue [#74](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/74))
* Items now spawn on ground (issue [#75](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/75))
* Fixed tooltip getting stuck on screen(issue [#76](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/76))
* Fixed pausing and unpausing during dialogue breaking the game(issue [#86](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/86))

## quests

* Tenement investigation quest can now be completed. (issue [#63](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/63))

## level

* Added trader at industrial area.
* Added map marker for Rob-In repair shop.
* Added every possible item for testing.
* General trader now sells and accepts more stuff.
* Fixed collision issues in an unfinished shack (issue [#66](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/66))
* Fixed collision issues an alley near bazaar (issue [#64](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/64))
* Fixed various collision issues.
* Disabled fishes until fishing is implemented.


# 22.11.2018 (0.0.1)

## main menu

* Added options menu
* Fixed missing radio static (issue [#9](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/9))

## general

* Death now opens pausemenu (issue [#12](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/12))
* Adjusted hunger and thirst rate.
* Added an effect when player takes damage.
* Added cookable soups.
* Added construction material items.
* Added sound when breaking bottles.
* Fixed crafting menu UI  (issue [#32](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/32))
* Fixed issues when breaking bottles.

## intro

* Fixed intro spelling mistakes (issue [#13](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/13))
* Fixed placeholder text flashing before intro (issue [#16](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/16))

## level

* Added more item spawns
* Added detail to off-limit areas
* Added detail to tenement opposite of Bazaar
* Added more item spawns
* Made it possible to obtain lockpicks.
* Improved farmland collisions
* Finished second checkpoint near parking garage
* Finished farm above O-Market
* Fixed collision issues near Osmo Olut factory (issue [#25](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/25))
* Fixed collision issues near barge (issue [#37](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/37))
* Fixed collision issues near church (issue [#44](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/44))
* Fixed buildings missing doors (issue [#17](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/17))
* Removed unpickable coins (issue [#42](https://github.com/loiste-interactive/Open-Sewer-Issues/issues/42))
* Removed random objects near market
