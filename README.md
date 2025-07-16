Fortnite Battle Royale - Itemshop Guide
Note

All Fortnite cosmetics can be found at Fortnite.GG/Cosmetics.

Requirements for Cosmetics
Version: Must be from Chapter 2 Season 5 (Version 15.30) or earlier.
Pricing: Use Fortnite’s official V-Bucks pricing.
Cosmetic ID: Must follow the correct format (see below).

Config File Structure
The item shop is defined using a JSON file. It contains slots for both daily (daily1 to daily6) and featured (featured1 to featured4) items, each with a price (in V-Bucks) and itemGrants (Cosmetic IDs).
{
    "//": "BR Item Shop Config",
    "daily1": {
        "itemGrants": [
            "AthenaBackpack:"
        ],
        "price": 0
    },
    "daily2": {
        "itemGrants": [
            "AthenaDance:"
        ],
        "price": 0
    },
    "daily3": {
        "itemGrants": [
            "AthenaCharacter:"
        ],
        "price": 0
    },
    "daily4": {
        "itemGrants": [
            "AthenaDance:"
        ],
        "price": 0
    },
    "daily5": {
        "itemGrants": [
            "AthenaPickaxe:"
        ],
        "price": 0
    },
    "daily6": {
        "itemGrants": [
            "AthenaPickaxe:"
        ],
        "price": 0
    },
    "featured1": {
        "itemGrants": [
            "AthenaCharacter:"
        ],
        "price": 0
    },
    "featured2": {
        "itemGrants": [
            "AthenaCharacter:"
        ],
        "price": 0
    },
    "featured3": {
        "itemGrants": [
            "AthenaCharacter:"
        ],
        "price": 0
    }
}
Examples:

Skin: "AthenaCharacter:Example"
Emote: "AthenaDance:Example"
Pickaxe: "AthenaPickaxe:Example"
Backbling: "AthenaBackpack:Example"
Glider: "AthenaGlider:Example"
Wrap: "AthenaItemWrap:Example"
Loading Screen: "AthenaLoadingScreen:Example"
Skydiving Contrail: "AthenaSkyDiveContrail:Example"

Helpful Tips
Use VS Code: It makes editing easier and shows you if something's wrong with your file.
Double-Check with AI: Tools like ChatGPT can help review your JSON before you test it.
