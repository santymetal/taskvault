# TaskVault with iPhone Shortcuts Support

## iPhone Shortcut Integration

TaskVault now supports URLs in the format: `https://your-site.github.io/taskvault/?task=<encoded-url>`

### Supported URL Parameters:
- `?task=<url>` - Your iPhone shortcut format
- `?url=<url>` - Standard web share format
- `?text=<url>` - Alternative format
- `?u=<url>` - Short parameter format

### Features:
- Automatic URL decoding for encoded parameters
- Detects iPhone shortcut vs web share source
- Shows appropriate success message
- Tags tasks with "shortcut" or "shared" automatically
- Auto-categorizes content (videos, articles, images, links)

### How Your iPhone Shortcut Should Work:

1. **Get Clipboard/Shared URL**
2. **Encode URL** (if needed): Use "Encode URL" action
3. **Open URL**: `https://santymetal.github.io/taskvault/?task=` + encoded URL

### Example URLs That Work:
- `https://santymetal.github.io/taskvault/?task=https%3A//youtube.com/watch%3Fv%3D123`
- `https://santymetal.github.io/taskvault/?task=https://twitter.com/status/123`
- `https://santymetal.github.io/taskvault/?url=https://example.com`

### Testing Your Shortcut:
1. Copy any URL in Safari
2. Run your shortcut
3. TaskVault should open and automatically create a task
4. Look for green success message: "✅ Added via iPhone shortcut"

### Benefits:
- One-tap task creation from any app
- Automatic categorization and tagging
- Works offline (saves to local storage)
- No manual typing required
- Perfect for capturing content on the go

The app will automatically decode URL-encoded parameters and create tasks with proper metadata.