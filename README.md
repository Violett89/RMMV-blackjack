# RMMV-blackjack
Simple Blackjack plugin for [RPG Maker MV](http://www.rpgmakerweb.com/products/programs/rpg-maker-mv)

## Description

This plugin creates a new scene with a Blackjack game where the player faces off against the dealer.

Suit names, face card names, card images and player face images are customizable.

## Installing the plugin

* Copy `GRZ_blackjack.js` into your project's js/plugins folder
* Either add the placeholder images or create images of your own:
  1. Create card images with names following the pattern `_value_of_suit_.png` such as 1_of_hearts.png and queen_of_spades.png
  2. Create 2 sets of four faces as shown in `CardPlayerFaces.png` for the player and dealer

## Using the plugin

### Settings

In the plugin settings, you can specify new names for face cards and/or card suits. See the in-editor project help file for more specifics.

### Plugin Commands

To run the plugin in-game, create an event with timing of your choosing and run `Plugin Command: Blackjack`

## Next Steps

Here are some features I'm considering for v1.0:

* Improved UI
* AI-controlled players
* Delaying the deck reshuffle (currently reshuffling every deal)
* Sound effects
* Additional graphical options: backgrounds, alternate face setups
