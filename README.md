# YouTube Bulk Unsubscribe Script

A browser script to help you easily unsubscribe from multiple YouTube channels at once.

## Features

- **Visual UI**: Shows progress directly on the YouTube page
- **Fast Processing**: Automatically opens and confirms unsubscribe dialogs
- **Success Detection**: Intelligently detects successful unsubscribes 
- **Progress Tracking**: Shows how many channels have been processed
- **Multi-language Support**: Works with English, Lithuanian and other UI languages

## How to Use

1. Go to your YouTube Subscriptions page: https://www.youtube.com/feed/channels
2. Press F12 to open your browser's Developer Tools
3. Go to the "Console" tab
4. Copy and paste the entire script into the console
5. Press Enter to run the script
6. Confirm when prompted to begin unsubscribing

## Controls

- **ESC key**: Pause/stop the script
- **STOP button**: Stop the script from the UI panel

## Requirements

- Modern web browser (Chrome, Firefox, Edge)
- JavaScript enabled
- YouTube account logged in
- Access to browser console

## How It Works

The script:
1. Identifies all subscribe buttons on the current page
2. Scrolls to each button and clicks it to open the unsubscribe dialog
3. Finds and clicks the confirmation button in the dialog
4. Detects if the unsubscribe was successful
5. Shows progress and statistics in a floating UI panel

## Troubleshooting

If you encounter issues:
- Make sure you're on the correct YouTube page (https://www.youtube.com/feed/channels)
- Try refreshing the page and running the script again
- Check if YouTube has changed their UI (which might break the script)
- Increase the delay values in the script's config section if actions are happening too quickly

## Disclaimer

Please see the DISCLAIMER.md file before using this script. Use at your own risk.

## License

This script is provided under the MIT License. See LICENSE file for details.
