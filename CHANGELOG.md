# Changelog

All notable changes to Watchfolio will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.1.0] - 2024-12-24

### 🎉 Initial Public Release

The first public release of Watchfolio brings a comprehensive media library manager with 300+ features across 20+ categories.

### ✨ Added

#### Library Management
- Track movies and TV shows with 6 custom statuses
- Personal ratings (1-10 scale) with descriptive labels
- Custom notes up to 2000 characters per item
- Favorites system for quick access
- Episode-level tracking for TV shows
- Season progress tracking with visual indicators
- Multi-select operations for bulk actions
- Drag & drop reordering within status groups
- Advanced filters (genre, network, status, favorites)
- Instant full-text search
- 8+ sort options
- Continue Watching section

#### Collections
- Create custom collections (50 per account limit)
- 500 items per collection
- Drag & drop reordering with persistent custom order
- Public/private toggle per collection
- Share collections with unique URLs
- Social media previews (Open Graph, Twitter Cards)
- Save/bookmark others' collections
- Duplicate collections (yours or public ones)
- Import collections from JSON
- Export collections to JSON or CSV
- Collection statistics (items, runtime, genres)
- Explore page for discovering public collections
- Search and filter within collections

#### Statistics & Analytics
- Comprehensive statistics dashboard with 10+ charts
- Viewing timeline (items added vs completed)
- Genre distribution pie chart
- Rating distribution chart
- Completion trend over time
- Day of week watching patterns
- Movie statistics (count, completion rate, avg rating, total time)
- TV show statistics (shows, episodes, completion rate)
- Episode tracking statistics
- Fun facts auto-generated insights
- Viewing predictions for planned items
- Profile statistics with privacy controls

#### AI-Powered Features
- Mood-based recommendations using Google Gemini AI
- Personalized suggestions based on:
  - Watch history and ratings
  - Genre preferences
  - Streaming subscriptions
  - Content preferences
  - Current mood/vibe
- Filter recommendations by content type, decade, duration
- Avoid suggesting items already in library

#### Search & Discovery
- Global search across movies, TV shows, celebrities
- Real-time search with instant results
- Multi-tab search interface
- Trending movies & TV shows
- Top Rated content
- Coming Soon releases
- 28 genres to explore
- 70+ networks to browse
- Popular celebrities section
- 1M+ titles from TMDB
- Movie franchise support (Marvel, DC, Star Wars, etc.)

#### Where to Watch
- Check streaming availability by country/region
- 70+ streaming providers supported
- Filter by service type (Streaming, Rent, Buy)
- 40+ countries supported
- Track your streaming subscriptions
- Filter to only show your services
- Provider logos and direct links
- Used in AI recommendations

#### User Profiles & Social
- Public profile pages with custom URLs
- Profile visibility toggle (public/private)
- Custom username and avatar
- Bio and profile customization
- Section-level privacy controls
- Favorite genres and content preferences
- Streaming service subscriptions management
- Public library view
- Collection showcase
- Profile statistics display
- Recent activity feed

#### Import & Export
- Library export to JSON or CSV
- Collection export (individual or batch)
- Filter exports by status & media type
- File size estimation
- Import from JSON or CSV
- File drop zone support
- Import preview with statistics
- Three merge strategies (smart merge, overwrite, skip)
- Data validation with Zod schemas
- Chunk-based processing for large files
- Web worker processing for 10k+ items

#### Cloud Sync & Offline
- RxDB local-first architecture
- Appwrite cloud sync backend
- Automatic real-time replication
- Conflict resolution
- Sync status indicator
- Manual sync trigger
- Auto-sync toggle
- Works completely offline after initial setup
- Queued sync when connection restored
- IndexedDB storage
- Instant performance

#### Keyboard Shortcuts
- 30+ keyboard shortcuts
- Navigation shortcuts (/, ?, Escape, Ctrl+B)
- Quick actions (Alt+W, Alt+P, Alt+C, Alt+F, Alt+R)
- Page navigation (Ctrl+1-5, Ctrl+0)
- Filter toggles (Ctrl+Shift+M, Ctrl+Shift+T)
- Import/Export shortcuts (Ctrl+I, Ctrl+E)
- Desktop-only shortcuts (Alt+N for Quick Add)
- Customizable and accessible
- Help modal with all shortcuts (? key)

#### Desktop Application
- Cross-platform support (Windows, macOS, Linux)
- Native performance with Tauri
- System tray integration
- Launch on startup option
- Deep linking support
- Native notifications
- Native file dialogs
- Custom titlebar
- Native menus (File, View, Library, Go, Help)
- Window minimize/maximize/close controls
- Auto-updates via Tauri updater
- Quick Add floating window (Alt+N)
- Platform-specific packages:
  - Windows: .exe installer, .msi package
  - macOS: .dmg for Intel & Apple Silicon
  - Linux: .deb, .AppImage, .rpm

#### Settings & Preferences
- Profile settings (avatar, name, bio, username)
- Email and password change
- Account deletion
- Default media status when adding
- Cloud sync toggle
- Auto-sync setting
- Favorite genres selection
- Content preferences
- Streaming subscriptions
- Show only subscribed providers toggle
- Animation toggle
- Confirmation dialogs toggle (per action)
- Privacy controls
- Device/session management

#### UI/UX
- Dark mode only (optimized for night viewing)
- Glass morphism design language
- Custom gradient system
- HeroUI component library
- Tailwind CSS 4 with custom utilities
- Framer Motion animations (60 FPS, toggleable)
- Responsive design (mobile, tablet, desktop)
- Touch-friendly mobile interface
- Status badges with color coding
- Modal system for all interactions
- Toast notifications
- Tooltips with keyboard hints
- Skeleton loaders
- Empty states with helpful messaging
- Error states with retry options
- File drop zones
- Progress bars and spinners
- Star ratings display
- Smooth page transitions

#### Authentication & Security
- Email/password signup and login
- Email verification required
- Session management with JWT
- Remember me functionality
- Password reset via email
- Account deletion option
- Device session management
- Secure password hashing
- Data encryption via Appwrite
- No tracking or analytics
- Privacy-first approach

#### Performance
- Instant local queries (RxDB in-memory)
- Background sync (non-blocking)
- Lazy loading images and components
- Code splitting per page
- Web workers for CPU-intensive tasks
- Debounced inputs (search, filters)
- Optimistic UI updates
- Infinite scroll over pagination
- Request deduplication
- Query caching (5 min stale time)

### 🔒 Security
- Encrypted cloud sync via Appwrite
- Secure authentication with JWT
- HTTPS only in production
- CORS protection
- Input sanitization and validation
- Password hashing (bcrypt via Appwrite)

### 📊 Statistics
- 300+ total features
- 20+ major feature categories
- 5 database collections
- 25+ pages
- 150+ components
- 30+ custom hooks
- 30+ keyboard shortcuts
- 10+ statistics charts
- 70+ streaming providers
- 40+ countries for watch providers
- 28 genres
- 1M+ movies & TV shows (TMDB)

---

## Versioning Strategy

Watchfolio follows [Semantic Versioning](https://semver.org/):

- **MAJOR** version (X.0.0) - Incompatible API changes, major redesigns
- **MINOR** version (0.X.0) - New features in a backwards-compatible manner
- **PATCH** version (0.0.X) - Backwards-compatible bug fixes

---

## Unreleased

_Stay tuned for upcoming features!_

### 🔮 Planned Features

See [FEATURES_ROADMAP.md](https://github.com/Zawalid/Watchfolio/blob/main/docs/FEATURES_ROADMAP.md) in the main repository for the full roadmap.

**High Priority:**
- Calendar view for upcoming releases
- More advanced episode tracking features
- Enhanced statistics with more chart types
- Collaborative collections
- Mobile native apps (iOS & Android)

---

## Release Notes Format

Future releases will follow this structure:

### [Version] - YYYY-MM-DD

#### 🎉 Added
- New features

#### ✨ Enhanced
- Improvements to existing features

#### 🐛 Fixed
- Bug fixes

#### 🔒 Security
- Security improvements

#### ⚡ Performance
- Performance improvements

#### 🗑️ Deprecated
- Features marked for removal

#### ❌ Removed
- Removed features

#### 📝 Changed
- Breaking changes

---

## Support

- **Report bugs:** [GitHub Issues](https://github.com/Zawalid/watchfolio-releases/issues/new?template=bug_report.md)
- **Request features:** [GitHub Issues](https://github.com/Zawalid/watchfolio-releases/issues/new?template=feature_request.md)
- **Ask questions:** [GitHub Issues](https://github.com/Zawalid/watchfolio-releases/issues/new?template=question.md)

---

[0.1.0]: https://github.com/Zawalid/watchfolio-releases/releases/tag/v0.1.0
