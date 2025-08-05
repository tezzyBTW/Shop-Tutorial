# Recon Item Shop Tutorial!

> **Note:**
> All Fortnite cosmetics are available at [Fortnite.gg](https://fortnite.gg/cosmetics?game=br&type=outfit&season=1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19).

---

## Configuration File Structure

The item shop is defined by a JSON file containing slots for daily (`daily1` through `daily6`) and featured (`featured1` through `featured6`) items. Each slot includes:

**How To Get ID: To get the CID, etc for an item, go to Fortnite.gg, click on any item, and copy the ID shown at the bottom right of the pop-up. Use that ID to replace "CID_TBD" in your config.**
```json
{
    "//": "BR Item Shop Config",
    "daily1": {
        "itemGrants": [
            "AthenaBackpack:Backpack-ID-here"
        ],
        "price": 0
    },
    "daily2": {
        "itemGrants": [
            "AthenaDance:Dance-ID-here"
        ],
        "price": 0
    },
    "daily3": {
        "itemGrants": [
            "AthenaGlider:Glider-ID-here"
        ],
        "price": 0
    },
    "daily4": {
        "itemGrants": [
            "AthenaDance:Dance-ID-here"
        ],
        "price": 0
    },
    "daily5": {
        "itemGrants": [
            "AthenaPickaxe:Pickaxe-ID-here"
        ],
        "price": 0
    },
    "daily6": {
        "itemGrants": [
            "AthenaPickaxe:Pickaxe-ID-here"
        ],
        "price": 800
    },
    "featured1": {
        "itemGrants": [
            "AthenaCharacter:CID-here"
        ],
        "price": 0
    },
    "featured2": {
        "itemGrants": [
            "AthenaCharacter:CID-here"
        ],
        "price": 0
    },
    "featured3": {
        "itemGrants": [
            "AthenaCharacter:CID-here"
        ],
        "price": 0
    },
    "featured4": {
        "itemGrants": [
            "AthenaCharacter:CID-here"
        ],
        "price": 0
    },
    "featured5": {
        "itemGrants": [
            "AthenaCharacter:CID-here"
        ],
        "price": 0
    },
    "featured6": {
        "itemGrants": [
            "AthenaCharacter:CID-here"
        ],
        "price": 0
    }
}
}
```
Important:
**Please set the item prices thoughtfully, adjusting them based on each skin’s rarity and exclusivity to ensure a balanced and fair shop experience.**


---

## Tips for Editing

* Use a JSON-aware editor like Visual Studio Code for better validation and formatting.
