# Discord Panel

Attention: Vivaldi still hasn’t solved numerous webpanel issues, including the whitelisting of cookies and reloading all webpanels when adding or removing a webpanel, or hiding the UI. What this means is we get logged out of Discord whenever we perform any of these actions, and logging back in is a tiresome undertaking, for password managers generally don’t work in webpanels. Therefore this project is archived now, I think it’s less painful using Discord in a tab overall right now.

A userscript for running Discord in a Vivaldi webpanel.
`Written by luetage and lonmcgregor`

## Features

* Introduces a button on top left to toggle the guilds wrapper, which saves horizontal space.
* Automatically hides the guilds when you leave the panel with the mouse.
* Both guilds wrapper and member view overlay.

## How to

On Vivaldi userscripts can be installed without the help of an additional extension like Tampermonkey or Violent Monkey. Simply enable developer mode on the extensions page and drag&drop the `discord.user.js` file onto it. Then open the Discord website as a webpanel by clicking the `+` sign in the panel container.

## Issues

Discord updates its web platform regularly and this can break features. The problem is that they change up the IDs and classes of elements all the time. I'm trying to stay on top of this, but it's hard. It would be far easier if Discord provided a mobile view for browsers, which would be used by Vivaldi's webpanels by default, but this doesn't seem to be happening.
