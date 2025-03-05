# NIKKE Character API

This repository contains data files for NIKKE: Goddess of Victory character information organized by rarity.
- Thank you Trid for helping me.

## Files

- nikke_r.py - Contains R rarity character data
- nikke_sr.py - Contains SR rarity character data
- nikke_ssr.py - Contains SSR rarity character data

## Usage

Import the character data dictionaries to access information:

```python
from data.nikke_r import R_CHARACTERS
from data.nikke_sr import SR_CHARACTERS
from data.nikke_ssr import SSR_CHARACTERS

# Example: Get information for a specific character
snow_white = SSR_CHARACTERS["snow white"]
print(f"Name: {snow_white['name']}")
print(f"Weapon: {snow_white['weapon']}")
print(f"Element: {snow_white['element']}")
```

## Data Structure

Each character entry includes:
- Name
- Weapon type
- Manufacturer
- Burst type
- Element
- Class
- Rarity
- Icon URL

## Credits

Character icons and images are sourced from [nikke.gg](https://nikke.gg) static assets.

## Note

This is an unofficial API created for educational and fan purposes only.
