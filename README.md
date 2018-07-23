# Discord Panel

A userscript for running Discord in a Vivaldi webpanel.
`Written by luetage and lonmcrgregor`

## Features

* Introduces a button on top left to toggle the guilds wrapper, which saves horizontal space.
* Automatically hides the guilds when you leave the panel with the mouse.
* Both guilds wrapper and member view overlay.
* Makes the main chat view more compact and tries to adjust the size of internal popups.

## How to

On Vivaldi userscripts can be installed without the help of an additional extension like Tampermonkey or Violent Monkey. Simply enable developer mode on the extensions page and drag&drop the `discord.user.js` file onto it. Then open the Discord website as a webpanel by clicking the `+` sign in the panel container.

## Issues

Discord updates its web platform regularly and this can break features. The problem is that they change up the IDs and classes of elements all the time. I'm trying to stay on top of this, but it's hard. It would be far easier, if Discord provided a mobile view for browsers, which would be used by Vivaldi's webpanels by default, but this doesn't seem to be happening.