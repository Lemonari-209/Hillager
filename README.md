# Sandwich Club SMP - Villager Catalogue

A standalone, single-file web application designed to track and manage villager trades for the Sandwich Club SMP. 

This tool helps players catalog trading halls, track best prices for enchantments, and calculate emerald costs for projects.

##  Quick Start

**No installation required.** 1. Download the `index.html` file.
2. Open it in any modern web browser (Chrome, Firefox, Edge).
3. Start logging villagers!

*Note: You need an active internet connection to load the libraries (React & Tailwind) from the CDNs.*

##  Features

###  Villager Management
- **Smart ID Generation:** Automatically generates organized IDs (e.g., `LIB-MND-001` for a Mending Librarian).
- **Vacancy Tracking:** View a visual grid of ID slots to fill gaps from deceased villagers.
- **Status Tracking:** Mark villagers as "Active" or "Terminated" (includes a manual death counter for unrecorded villagers).

###  Trading & Economy
- **Buy & Sell Support:** Log items players buy (e.g., Diamond Pickaxe) and items players sell (e.g., Sticks/Flesh).
- **Shopping Cart:** Add specific trades to a cart to calculate the total Emeralds and raw materials needed for a project.
- **Profit Calculation:** See how many emeralds you will gain from selling a haul of items.

###  Enchantment Library
- Visualizes all standard Minecraft enchantments.
- Automatically detects if an enchantment is "Collected" based on your active villagers.
- Highlights the location and price of the cheapest available book for every enchantment.

###  Data & Settings
- **Auto-Save:** Data is automatically saved to your browser's Local Storage.
- **Import/Export:** Export your catalogue to a `.json` file to share with server-mates or backup your data.
- **Custom Tags:** Define custom short-codes for items in the Settings menu (e.g., map "Golden Carrot" to "GLD").

##  Tech Stack

- **Core:** HTML5, JavaScript (ES6+)
- **UI Framework:** React 18 (via CDN)
- **Styling:** Tailwind CSS (via CDN)
- **Compiler:** Babel Standalone

##  Usage Guide

### Logging a New Villager
1. Click **"Log Villager"**.
2. Select the profession and location.
3. Add trades. The system will attempt to auto-generate a 3-letter tag (e.g., "Protection IV" -> "PRT").
4. You can "Star" a specific trade to make it the primary tag for that villager's ID.

### Using the Shopping Cart
1. Browse the list and click the **+** icon next to any trade.
2. Open the **Shopping Bag** icon in the top right.
3. Adjust quantities. The bottom summary will tell you exactly what to bring to the trading hall.

##  Contributing

Since this is a single-file application, you can simply edit the `index.html` file directly to make changes.
