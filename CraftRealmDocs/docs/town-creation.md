---
sidebar_position: 6
title: Create a town
---

# How to create and manage a town

## Create a town

Creating a town costs 64 gold.

Stand in the location where you want the town to be. Run command `/t new`, this will spend those gold ingots and create a single chunk owned by you. You now have a town with the size of 1 chunk. 

:::info

There's a lot to be learned about towns. It can feel overwhelming at first but don't worry, just learn as you go. Once you've made a town, that chunk is protected so don't rush to do any more.

:::

## Town basics​

You can spawn directly to your town with `/t spawn`.

Invite residents with `/t invite`.

Mayors can join add their town to a nation by using the command `/n join`. You can only join nations whose capital’s homeblock is within 3000 blocks of your town’s homeblock. The nation must either be open as seen on `/n nation_name` or your town has to be invited. Accept the invite using `/t invite accept nation_name`.

:::tip

Avoid giving your residents a pre-made house and too much free gear. Let your residents grow and develop with your town. This improves resident retention.

Think carefully before joining a Nation. Weigh the advantages and disadvantages.

:::

## Town permissions​

To protect your town against rogue residents, you can run `/t set perm off` to set it so that no residents can interact with anything. Not doing this allows your town to be griefed or have it's items stolen by residents.

Town permissions manage what residents has access to interact with inside a town. There are 4 permission types:

- **Build** - Allow residents to place blocks inside the town.
- **Destory** - Allow residents to destory blocks inside the town.
- **Switch** - Manages permission to interact with chests,furnaces, levers, hoppers, droppers and blocks with similar nature.
- **Itemuser** - Manages permission to interact with water, lava, buckets, lighters, bonemeal, enderpearls, bottles and items with - similar nature.

A safe default for new mayors is to disable all above permissions with `/t set perm off`. It's also possible to change permissions specifically for allies and outsiders. For example, `/t set perm ally build on` would allow residents of allied nations to build inside the town. It's also possible to edit permissions for individual claims, plots. More on that later.

## Town ranks​

Mayors can give ranks to residents with `/t rank add {username} {rank}`.

**Assistant** gives the player full access to town plots regardless of ownership, access to most town commands excluding `/t unclaim`, `/t set mayor`, `/t delete` etc. This rank should only be given to the most trusted citizens as it could be detrimental to your town. They can kick everyone except the mayor and other councillors. They can also break everything, steal everything, withdraw all your town gold and toggle all perms on for every other player.

**Helper** can use the switch permission in any plots of the town.

## Town commands

| Command | Description |
| ----------- | ----------- |
|/t {town}|View information on specified town|
|/t here|View information on town at current location|
|/t list|List of all towns|
|/t leave|Leave town|
|/t new|Create a new town|
|/t add {resident}|Add resident to town|
|/t kick|Kick resident from town|
|/t spawn|Teleport to town spawn|
|/t claim|Claim chunk|
|/t withdraw|Withdraw gold from town bank|
|/t deposit|Deposit gold to town bank|
|/t rank add {player} {rank}|Give player specified rank|
|/t rank remove {player} {rank}|Remove player's specified rank|
|/t set|Set board/mayor/homeblock (spawn)/perm for town|
|/t toggle|Toggle explosion/fire/mobs/pvp for town|