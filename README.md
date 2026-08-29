# Auction-House-Skript

A powerful and customizable Minecraft Auction House system made with Skript.

## 👋 Introduction

Hello everyone, I'm Elyther!

This project is a simple and modern Auction House system for Minecraft servers. It allows players to list their items for sale, browse other players' listings, search for specific items, sort listings by price, and purchase items through a convenient GUI.

The system is designed to be easy to install and use, even if you are hosting your server on platforms such as Aternos.

## ✨ Features

- 🏪 GUI-based Auction House
- 💰 Player item selling system
- 🛒 Item purchasing system
- 🔎 Item search system
- 📊 Listing sorting system
- 📄 Multiple pages
- 🔄 Refresh listings
- 📦 My Listings menu
- ❌ Remove your own listings
- ✅ Purchase confirmation system
- 💵 Automatic price formatting
- ⚡ Quick and simple commands
- 👑 Server listing support
- 🔐 Admin commands
- 💾 Auction House data storage

## 📋 Requirements

You only need:

- **Skript**

No additional plugins are required for the basic Auction House system.

## 📥 Installation

### 1. Install Skript

Make sure the **Skript** plugin is installed and enabled on your Minecraft server.

### 2. Create the Script File

Go to:

`plugins/Skript/scripts/`

Create a new file called:

`Auction.sk`

### 3. Add the Code

Copy the code from this repository and paste it into:

`Auction.sk`

Your folder should look like this:

```text
plugins/
└── Skript/
    └── scripts/
        └── Auction.sk
4. Reload the Script

After uploading the file, run:
/sk reload Auction
If there are no errors, the Auction House is ready to use.

🌐 Aternos Installation

If you are using Aternos, go to:

Files → plugins → Skript → scripts

Create or open:

Auction.sk

Paste the code into the file and save it.

Then reload Skript or restart your server.

🎮 Commands

Player Commands

/ah
Opens the Auction House.

/ah sell <price>
Lists the item you are holding for sale.
Examples:
/ah sell 500
/ah sell 10k
/ah sell 2.5m
/ah sell 1b

Purchase Confirmation
/ahconfirm on
/ahconfirm off
Enable or disable purchase confirmation.

Admin Commands

/ahclear
Clears all Auction House listings.

/ahcheck
Displays the current Auction House listings.

/ahserverlist <price>
Adds an item as a server listing.

💰 Price Formats

The Auction House supports shortened prices:

🛠️ Customization

You can customize the Skript to fit your server, including:
	•	GUI names
	•	Messages
	•	Item display
	•	Prices
	•	Auction limits
	•	Sorting options
	•	Purchase confirmation
	•	Server listings

⚠️ Important

Before installing the script on a live server, it is recommended to make a backup of your server files and Auction House data.

Make sure your Skript version is compatible with your Minecraft server version.

📜 License

You are free to use and modify this project for your Minecraft server.

If you share a modified version publicly, please consider giving credit to the original creator.

⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

Thank you for checking out Auction-House-Skript!

Created by Elyther

