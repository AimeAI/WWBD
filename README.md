# GRANT RECON v2.1

**Mission-Critical Grant Discovery & Management Platform for Wounded Warriors & PTSD Treatment Organizations**

---

## Overview

Grant Recon is a comprehensive grant management system designed specifically for:
- Wounded warriors and veterans with PTSD
- Non-profit organizations supporting military mental health
- PTSD treatment centers and research programs
- Veteran transition and family support services

### The Problem
Finding and managing grant opportunities is overwhelming:
- Grants scattered across hundreds of government and corporate websites
- Deadlines easy to miss
- No central tracking system
- Manual research takes 20+ hours per month

### The Solution
Grant Recon provides:
- **50+ curated, verified grant sources** focused on veteran/PTSD causes
- **Smart deadline tracking** with visual urgency indicators
- **Application workflow management** (6-stage status tracking)
- **Export capabilities** (JSON, CSV, Calendar integration)
- **100% local, private data** (no external servers)
- **Zero cost** to use

---

## Quick Start

1. **Open `grant-tracker-v2.1.html`** in any modern browser
2. **Enter your keywords** (e.g., "PTSD, Mental Health, Veterans")
3. **Click "INITIATE SCAN"** to discover matching grants
4. **Track promising grants** with the "+ TRACK" button
5. **Switch to "MY GRANTS" tab** to manage your pipeline

That's it. No installation, no signup, no credit card.

---

## Key Features

### 🎯 Grant Discovery
- 50+ verified sources across Canada (Federal, Provincial, Corporate, Foundations)
- Smart keyword filtering
- Jurisdiction scope selection
- Real-time search results

### ⏰ Deadline Management
- Color-coded urgency indicators:
  - **RED**: Due within 7 days (urgent!)
  - **ORANGE**: Due within 30 days
  - **GREEN**: 30+ days away
  - **GRAY**: Rolling deadlines
- Automatic day countdown
- Calendar export (.ics) for Google Calendar, Outlook, Apple Calendar

### 📊 Application Tracking
Track each grant through 6 stages:
1. **Discovered** - Just found it
2. **Researching** - Reviewing requirements
3. **Preparing** - Gathering documents
4. **Submitted** - Application sent
5. **Approved** - Funding secured!
6. **Rejected** - Learn and iterate

### 📝 Note-Taking System
For each tracked grant, document:
- Eligibility requirements
- Required documents
- Grant officer contacts
- Phone call insights
- Internal deadlines
- Strategy notes

### 💾 Data Persistence
- Auto-saves all data to browser localStorage
- No external servers (your data stays private)
- Export backups anytime (JSON format)

### 📤 Export Capabilities
- **JSON**: Complete data backup with all notes and status
- **CSV**: Excel-compatible spreadsheet for board reports
- **Calendar (.ics)**: Import all deadlines into your calendar app

---

## Database Coverage

### Federal Programs (12 grants)
Veterans Affairs Canada, CIHR, ESDC, Public Health Agency, Mental Health Commission, Innovation Canada

### Corporate & Foundations (25+ grants)
Bell Let's Talk, RBC, TD, Scotiabank, Google.org, Manulife, Home Depot, Walmart, Costco, Intact, Mastercard Foundation, McConnell Foundation, Metcalf Foundation

### Veteran-Specific Charities (7 grants)
True Patriot Love, Wounded Warriors Canada, VETS Canada, Legion National Foundation

### Provincial Programs (13+ grants)
- **Ontario**: Trillium Foundation, Mental Health & Addictions Fund, CAMH, United Way GTA
- **British Columbia**: Gaming Grants, Vancouver Foundation, BC Health
- **Alberta**: Community Initiatives Program, Calgary Foundation, Edmonton Foundation
- **Quebec**: Community Action Fund, Montreal Foundation
- **Nova Scotia**: Health Authority Innovation Fund, Community Foundation

### Mental Health Focused (8 grants)
CAMH, Mental Health Commission, Bell Let's Talk, Jack.org, Kids Help Phone, RBC Mental Health

**Grant Amounts**: From $1,000 to $5,000,000

---

## Files in This Project

```
wwbd/
├── grant-tracker-v2.1.html    # Main application (OPEN THIS)
├── wwbd.html                  # Original v2.0 baseline
├── README.md                  # This file
├── USER_GUIDE.md             # Detailed usage instructions
├── PROJECT_ANALYSIS.md       # Strategy, roadmap, technical docs
└── .git/                     # Version control
```

---

## Documentation

- **USER_GUIDE.md**: Complete instructions, tips, troubleshooting
- **PROJECT_ANALYSIS.md**: Strategic analysis, roadmap, database expansion plans
- **This README**: Quick overview and getting started

---

## Version History

### v2.1 (Current) - November 19, 2025
- Expanded database to 50+ verified grant sources
- Added grant tracking system (6 status stages)
- Implemented deadline tracking with urgency indicators
- Built note-taking system for each grant
- Added localStorage persistence (auto-save)
- Created export system (JSON, CSV, Calendar)
- Enhanced UI with dual-tab navigation
- Improved filtering and search capabilities

### v2.0 - November 19, 2025
- Initial release with 10 grants
- Basic keyword search
- Tactical terminal-style interface
- Deep search protocol (Google Dork integration)

---

## Roadmap

### v2.2 - Collaboration (Next)
- Share grant lists via URL
- Team assignment features
- JSON import functionality
- Comment threads on grants

### v2.3 - Document Management
- Application checklist builder
- Document vault (track prepared docs)
- Reusability scoring

### v3.0 - Intelligence Layer
- Smart matching algorithm (auto-score grant fit)
- Dashboard analytics
- Visual calendar view
- Email notifications
- Web scraping automation

---

## Technical Details

**Architecture**: Single HTML file with embedded CSS and JavaScript
**Storage**: Browser localStorage API
**Dependencies**: None (pure HTML/CSS/JS)
**Browser Support**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
**Mobile**: Responsive design, works on tablets and phones

**Why single-file?**
- Easy to deploy (no build process)
- Works offline
- No hosting required
- Easy to backup (just copy the file)
- Privacy-focused (no external servers)

---

## Version Control

Full git history available:
- Initial commit (v2.0 baseline)
- v2.1 enhancement commit

To see changes:
```bash
git log --oneline
git diff v2.0 v2.1
```

To roll back if needed:
```bash
git checkout <commit-hash> -- grant-tracker-v2.1.html
```

---

## Data Privacy

**What's stored locally:**
- Grant IDs you've tracked
- Status updates
- Your notes
- Export timestamps

**What's NOT stored:**
- Your organization name
- Contact information
- Financial data
- Application documents

**Where it's stored:**
Browser localStorage (never leaves your computer)

**How to backup:**
Export to JSON regularly (weekly recommended)

---

## Support

Questions? Issues? Feature requests?
1. Check USER_GUIDE.md
2. Review PROJECT_ANALYSIS.md
3. Submit via your preferred channel

---

## Contributing

### Found a grant we're missing?
Submit with these details:
- Grant name and organization
- Amount range
- Deadline (or "rolling")
- Link to application
- Relevant tags (PTSD, Veterans, etc.)

### Want to improve the code?
- Fork and submit pull requests
- Check PROJECT_ANALYSIS.md for roadmap priorities
- Follow existing code style

---

## License

Open source for the veteran community.
Use freely, modify, distribute.
Give credit where helpful.

---

## Mission Statement

**For the warriors who've served our country and now battle invisible wounds:**

Grant Recon exists to remove barriers between you and the funding you need to heal, transition, and thrive. Every grant found is a step toward recovery. Every deadline met is a victory. Every dollar secured is ammunition in the fight against PTSD.

We built this because navigating bureaucracy shouldn't be another battle.

**Your mission: Secure the funding.**
**Our mission: Make it easier.**

---

**◆ GRANT RECON v2.1 - MISSION CONTROL**

*Built with purpose. Powered by community. Focused on impact.*

---

## Credits

**Design & Development**: Claude Code with frontend-design skill
**Database Research**: Compiled from public sources (government sites, foundation portals)
**Target Audience Insight**: Wounded warriors, veteran organizations, PTSD treatment providers
**Last Updated**: November 19, 2025

**Special Thanks**: To the organizations doing the real work—treating PTSD, supporting transitions, helping families heal. This tool is for you.
