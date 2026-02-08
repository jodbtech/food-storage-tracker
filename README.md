# 🥗 Food Tracker

A simple, free, and powerful web app to track your fridge and pantry contents, monitor expiration dates, and reduce food waste. Works completely offline with no account required.

![Food Tracker](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

### 📸 Photo Attachments
- Attach photos to any food item for quick reference
- View full-size images with a single tap
- Perfect for remembering what items look like or checking labels later

### 🏷️ Smart Categories
Organize your food with 10 built-in categories:
- 🥛 Dairy
- 🥬 Produce
- 🥩 Meat & Poultry
- 🐟 Seafood
- 🌾 Grains & Bread
- ❄️ Frozen
- 🥤 Beverages
- 🧂 Condiments
- 🍿 Snacks
- 📦 Other

### 🔍 Powerful Search & Filtering
- **Search** - Instantly find items by name
- **Filter by category** - View only specific food types
- **Filter by location** - Separate fridge and pantry views
- **Filter by expiration** - Quickly see expired items or those expiring soon
- **Combine filters** - Use multiple filters together for precise results

### 🚨 Expiration Alerts
Color-coded visual alerts keep you informed:
- 🔴 **Red** - Expired or expiring today
- 🟡 **Yellow** - Expiring within 3 days
- 🔵 **Blue** - Expiring within 4-7 days
- 🟢 **Green** - More than 7 days remaining

### 👨‍🍳 Recipe Suggestions
- Automatically suggests recipes based on items expiring within 3 days
- 20 built-in recipes from quick meals to family dinners
- Shows how many of your expiring ingredients match each recipe
- Helps reduce food waste by using items before they expire

### 📱 Mobile-Friendly
- Responsive design works perfectly on phones, tablets, and desktop
- Add to your phone's home screen for app-like experience
- Works completely offline after initial load
- No installation or app store needed

### 🔒 Privacy-First
- All data stored locally on your device
- No account required
- No data sent to external servers
- Your food inventory stays completely private

## 🚀 Getting Started

### Online Version
Visit the live app: `https://[your-username].github.io/[repo-name]/`

### Add to Home Screen

**iPhone:**
1. Open the app in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Name it "Food Tracker" and tap Add

**Android:**
1. Open the app in Chrome
2. Tap the menu (3 dots)
3. Tap "Add to Home screen"
4. Name it and tap Add

### Offline Use
Once loaded, the app works completely offline. Your data persists even when you close the browser.

## 📖 How to Use

### Adding Items
1. Click the photo area to attach an optional reference photo
2. Enter the item name (e.g., "Milk", "Chicken Breast")
3. Select a category from the dropdown
4. Choose location (Fridge or Pantry)
5. Set the expiration date
6. Add quantity if desired (optional)
7. Click "Add Item"

### Finding Items
- Use the search bar to type item names
- Select filters to narrow down your view
- Click "Clear all" to reset filters

### Managing Items
- Click the photo thumbnail to view full-size
- Click the trash icon to delete items
- Items are automatically sorted by expiration date

### Recipe Suggestions
- When you have items expiring within 3 days, a recipe banner appears
- Click "Show Recipes" to see suggestions
- Recipes show cooking time and how many ingredients you have

## 🛠️ Technical Details

- **Frontend:** Pure HTML, CSS (Tailwind), and React
- **Storage:** Browser localStorage (no backend required)
- **Size:** Single HTML file (~20KB)
- **Dependencies:** React 18, Tailwind CSS (loaded via CDN)
- **Browser Support:** All modern browsers (Chrome, Firefox, Safari, Edge)

## 💾 Data Storage

All data is stored locally in your browser using localStorage:
- Items persist between sessions
- Photos stored as base64 strings
- No size limit for reasonable use (typically 5-10MB available)
- Data never leaves your device

## 🌟 Use Cases

- **Home cooks** - Track ingredients and plan meals
- **Meal preppers** - Monitor prepped food freshness
- **Families** - Reduce food waste and save money
- **Students** - Keep dorm fridge organized
- **Anyone** - Stop throwing away forgotten food

## 🔄 Backup & Export

To backup your data:
1. Open browser developer tools (F12)
2. Go to Application → Local Storage
3. Find `foodTrackerItems` key
4. Copy the value to save elsewhere

To restore:
1. Open developer tools
2. Paste the value back into `foodTrackerItems`
3. Refresh the page

## 🤝 Contributing

This is a personal project, but feel free to fork and customize for your own use!

## 📄 License

MIT License - Feel free to use, modify, and distribute.

## 🐛 Known Limitations

- Photos stored as base64 can increase storage usage
- Large numbers of items (500+) may slow performance
- Recipe suggestions are basic pattern matching
- No cloud sync between devices

## 💡 Future Ideas

- Export data as CSV
- Import from grocery receipts
- Barcode scanning
- Nutritional information
- Meal planning calendar
- Shopping list generation
- Multi-language support

## 📞 Support

If you encounter issues:
1. Make sure you're using a modern browser
2. Clear browser cache and reload
3. Check browser console for errors
4. Try in private/incognito mode

## 🙏 Acknowledgments

Built with React, Tailwind CSS, and lots of coffee ☕

---

**Stop wasting food. Start tracking today!** 🥗✨
