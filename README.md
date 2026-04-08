# onemoresend auto drainer

Auto-drain extension for https://throne.com/onemoresend

## Setup

1. **Enable Developer Mode in Chrome**
   - Go to `chrome://extensions/`
   - Toggle "Developer mode" ON (top right)

2. **Load the Extension**
   - Click "Load unpacked"
   - Select this `onemoresenddrainer` folder
   - Extension loads with icon in toolbar

3. **Run the Drain**
   - Go to https://throne.com/onemoresend
   - Click the extension icon
   - Select an item when modal appears
   - Extension auto-drains: add to cart → checkout → pay

## Wishlist Items

- **Popcorn <3** - $8.00
- **breakfast <3** - $15.00
- **Gym membership** - $25.00
- **Nails ~** - $50.00
- **Phone bill** - $75.00
- **shopping spree 💋** - $100.00

## Features

- Select item once, remembers choice
- Auto-clicks add to cart
- Auto-opens checkout
- Sets custom name as "autodrainer" at payment
- Auto-submits payment
- Spawns images from onemoresend image service
- Loops continuously until tab is closed

## Image Setup

Images are automatically pulled from:
```
https://mikpics-production.up.railway.app/api/random-image
```

Images spawn every 0.25 seconds during drain (10 images instantly, then 1 every 250ms).

## Notes

- Make sure card details are saved in Throne beforehand
- Extension runs only on throne.com/onemoresend
- Close tab to stop draining
- Check console (F12) for debug logs
