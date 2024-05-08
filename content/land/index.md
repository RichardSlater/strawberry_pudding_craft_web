+++
title = 'Land'
date = 2024-05-18T12:14:07Z
draft = false
type = 'page'
layout = 'page'
featured_image = 'images/hero-land.jpeg'
menus = 'main'
+++

Land is the mechanism Strawberry Pudding Craft uses to protect player builds, spawn, and the wild. Land claims reduce the chances of bad actors griefing the server and are integral to the economy.

All players are able to claim lands using Strawberries (🍓, our in-game currency) to create a Town; you can earn 🍓 by completing quests in-game; you will then need to transfer 🍓 into the town's bank account to be able to pay upkeep.

The land system is built using Towny; you can read the [complete player guide](https://github.com/TownyAdvanced/Towny/wiki/How-Towny-Works) on their GitHub Wiki.

## Creating a Town

From the in-game chat, type the following (replace `{townname}` with the name of your town):

```
/town new {townname}
```

This will debit your account and claim initial blocks.

## Extending a Town

You can claim adjacent blocks with the following command; each additional block will cost upkeep.

```
/town claim
```

## Joining a Town

There are two ways to join a town; the first is to be invited by the Mayor:

```
/town add {playername}
```

The second is to request to join:

```
/town join {townname}
```

Not all towns will accept new members; you can check which towns are open with `/town list by open`.

