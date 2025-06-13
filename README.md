# TaskVault Enhanced - Your Secondary Brain

## New Features Added ✨

### 1. Web Share Support
- Share links directly to TaskVault from any app
- Automatic category detection (videos, images, links)
- Instant task creation from shared content

### 2. Enhanced Task Management
- **Edit existing tasks** - Click the ✏️ button on any task
- **Priority levels** - High, Medium, Low with color coding
- **Time support** - Add specific times along with dates
- **Tags system** - Organize tasks with hashtags
- **Better task sorting** - Priority-based with completion status

### 3. Notifications & Reminders
- Browser push notifications for overdue tasks
- Daily reminders for today's tasks
- Visual notification indicators in the header
- Customizable notification times in settings

### 4. Additional Features
- **Floating add button** - Quick access to add tasks
- **Enhanced statistics** - Including today's and overdue counters
- **Data export/import** - Backup and restore your tasks
- **Settings panel** - Configure notifications and preferences
- **Improved mobile UI** - Better touch targets and responsiveness
- **Visual priority indicators** - Color-coded task borders
- **Overdue task highlighting** - Red backgrounds for urgent tasks

### 5. Technical Improvements
- **Better mark done functionality** - Fixed completion issues
- **PWA enhancements** - Improved offline functionality
- **Share target registration** - Appears in device share menus
- **Background sync** - Notifications work even when app is closed

## Usage Instructions

### Adding Tasks
1. Use the floating "+" button in bottom right
2. Fill in task details including priority and tags
3. Set date and time for deadlines
4. Tasks auto-sort by priority and completion

### Sharing to TaskVault
1. In any app, use the share button
2. Select "TaskVault" from share menu
3. Task automatically created with shared content
4. Video links auto-categorized as videos

### Managing Tasks
- **Complete**: Click "Mark Done" button
- **Edit**: Click ✏️ button to modify any task
- **Delete**: Click 🗑️ button to remove task
- **Search**: Use search bar to find tasks by title, content, or tags

### Notifications
1. Open Settings (⚙️ button in header)
2. Enable notifications
3. Set preferred notification time
4. Grant browser notification permissions when prompted

### Data Management
- **Export**: Settings → Export Data (downloads JSON backup)
- **Import**: Settings → Import Data (restore from backup)
- All data stored locally in browser

## Deployment
Upload all files to your GitHub repository:
- index.html (main app)
- manifest.json (PWA configuration)
- sw.js (service worker)
- icon-192.svg, icon-512.svg (app icons)
- .nojekyll (prevents Jekyll processing)

No server required - fully client-side application!

## Browser Support
- Chrome/Edge (full features)
- Safari (most features, limited notifications)
- Firefox (most features)
- Mobile browsers (optimized experience)

## Privacy
- All data stored locally on your device
- No external servers or tracking
- Works completely offline
