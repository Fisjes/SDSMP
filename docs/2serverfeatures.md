---
sidebar_label: "Server Features"
sidebar_position: 3
---

# Server Features

## Economy
We use an emerald-based economy system. Emeralds are exchangeable for **Softcoins**, our server currency, at a rate of 1 emerald = 10 Softcoins.

**Exchanging emeralds for Softcoins:**
- `/exchange <amount>` — exchange a specific number of emeralds
- `/exchange` — exchange all emeralds in your inventory at once

**Withdrawing Softcoins back to emeralds:**
- `/withdraw <amount>` — converts Softcoins back to emeralds (must be in multiples of 10)

You can check your balance with `/bal` and pay other players with `/pay <player> <amount>`.

## Auctioning
Put items up for auction and let players bid against each other in real time. Auctions last **30 seconds**, with reminders at 15s, 10s and 5s remaining. A last-second bid extends the timer by 15 seconds.

**Starting an auction:**
- `/auction hand <price>` — auctions everything you're holding in your hand
- `/auction start <amount> <price>` — auctions a specific amount of the item in your hand

**Bidding:**
- `/bid` — auto-bids current price + 1 Softcoin
- `/bid <amount>` — bids a custom amount (must be at least current bid + 1)

**Other:**
- `/auction info` — shows the current auction, highest bidder and time remaining
- `/auction stop` — sellers can cancel their own auction at any time, item is returned and the highest bidder is refunded

The winner receives the item automatically. The seller receives the winning bid in Softcoins.

## Player Shops
Use [Universal Shops](https://modrinth.com/mod/universal-shops) to set up your own shop. Craft a **Trade Shop block** (4 planks + 1 wool + 1 iron ingot), place it against a chest, and configure what you're selling and at what price. Other players can browse and buy directly from your shop.

## Land Claiming
Protect your builds with [Flan](https://modrinth.com/mod/flan). Claim your territory using a **golden hoe** and control exactly who is allowed to build, open containers or interact on your land. Use `/flan` to manage your claim permissions and groups.

## Custom Avatars with Figura
We have [Figura](https://modrinth.com/mod/figura) installed, a client-side mod that lets you create, import and wear fully custom 3D avatars. Make yourself look however you want.

## Painting with Joy of Painting
[Joy of Painting](https://modrinth.com/mod/joy-of-painting) lets you paint your own custom paintings and hang them on walls like actual art. Decorate your base however you like.

## Waystones & Warp Pads
Getting around is easy with [Waystones](https://modrinth.com/mod/waystones). Teleport to towns, bases and points of interest without the hassle of travelling.

## Block Customization with Rechiseled
[Rechiseled](https://modrinth.com/mod/rechiseled) lets you alter the patterns of almost any block, giving you way more variety and detail in your builds.

## Terralith World Generation
Our world uses [Terralith](https://modrinth.com/mod/terralith), an advanced terrain generator that overhauls world generation and adds over 100 new biomes to explore.

## Home & Teleport Commands
Set personal home points with `/home set [name]` and teleport back anytime. Use `/tpa` to request a teleport to another player, or `/tpahere` to request they come to you.

## Proximity Voice Chat
We have [Simple Voice Chat](https://modrinth.com/mod/simple-voice-chat) set up, which lets you talk to players near you in-game via proximity chat. The closer you are, the louder they sound.