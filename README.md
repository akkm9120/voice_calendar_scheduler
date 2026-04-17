# Voice Calendar Scheduler

A simple web application that listens to your voice and marks your free days on a calendar. Perfect for quickly scheduling your availability without typing.

## Features

✨ **Voice Input** - Speak naturally to add free days to your calendar
🗓️ **Calendar View** - Visual calendar display with highlighted free days
💾 **Persistent Storage** - Your schedule saves automatically (no refresh needed)
🎤 **Accent-Friendly** - Fuzzy matching handles mispronounced dates
✏️ **Manual Editing** - Click dates to toggle or remove them
🌙 **Dark Theme** - Easy on the eyes

## How to Use

1. **Start Listening** - Click the microphone button
2. **Speak Your Free Days** - Try phrases like:
   - "I'm free on January 15th and 20th"
   - "Mark me free next Monday and Friday"
   - "I'm free the 5th, 10th, and 22nd"
3. **View Results** - Calendar updates in real-time with green highlighted dates
4. **Navigate Months** - Use Prev/Next buttons to check other months
5. **Edit Manually** - Click any date to toggle it, or use the ✕ button to remove

## Browser Support

Requires a browser with Web Speech API support:
- ✅ Chrome/Chromium (Edge, Brave, Opera)
- ✅ Safari (iOS 14.5+)
- ✅ Firefox (with flags enabled)

## Technical Highlights

- **Fuzzy Matching Algorithm** - Levenshtein distance handles accent variations and mispronunciations
- **Local Storage** - All data stored in browser, no server needed
- **Responsive Design** - Works on desktop and mobile
- **No Dependencies** - Vanilla JavaScript, pure HTML/CSS

## Data Privacy

Your calendar data is stored only in your browser's local storage. Nothing is sent to any server.

## Tips

💡 Say month names clearly or slightly mispronounce them—fuzzy matching will figure it out
💡 Numbers (dates) are recognized by themselves, so "5, 10, 22" works even without "the"
💡 Click "Clear all" to reset everything (with confirmation)
💡 Your data persists until you clear browser storage or manually reset
