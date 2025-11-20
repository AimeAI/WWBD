# GRANT RECON v2.1 - User Guide

## Mission-Critical Grant Tracking for Wounded Warriors & PTSD Treatment Organizations

---

## Quick Start

1. **Open** `grant-tracker-v2.1.html` in any modern web browser
2. **Enter keywords** relevant to your organization (e.g., "PTSD, Veterans, Mental Health")
3. **Click "INITIATE SCAN"** to discover matching grants
4. **Track grants** by clicking the "+ TRACK" button on any grant card
5. **Switch to "MY GRANTS" tab** to manage your tracked opportunities

---

## Key Features

### 1. Grant Discovery
- **50+ Verified Grant Sources** across Canada
  - Federal programs (Veterans Affairs, CIHR, ESDC, etc.)
  - Provincial grants (Ontario, BC, Alberta, Quebec, Nova Scotia)
  - Corporate foundations (Bell, RBC, TD, Google, etc.)
  - Veteran-specific charities (True Patriot Love, Legion, Wounded Warriors, etc.)
  - Mental health organizations (CAMH, Mental Health Commission, Jack.org)

- **Smart Filtering**
  - Keyword search across titles, descriptions, and tags
  - Jurisdiction scope (Federal, Provincial, All)
  - Status filtering (Discovered, Researching, Preparing, Submitted)

### 2. Deadline Tracking
Each grant displays a color-coded deadline indicator:
- **RED (⚡)** - Due within 7 days (URGENT!)
- **ORANGE (◆)** - Due within 30 days
- **GREEN (◇)** - More than 30 days away
- **GRAY (⊚)** - Rolling deadline (apply anytime)

The system automatically calculates days remaining and prioritizes urgent opportunities.

### 3. Grant Tracking System
Once you click "+ TRACK" on any grant, you can:
- **Monitor application status** through 6 stages:
  - Discovered (just found it)
  - Researching (reviewing requirements)
  - Preparing (gathering documents)
  - Submitted (application sent)
  - Approved (funding secured!)
  - Rejected (learn and move forward)

- **Add notes** for each grant:
  - Eligibility requirements
  - Required documents
  - Contact person names
  - Follow-up dates
  - Any insights from phone calls

### 4. Data Persistence
All your data saves automatically to your browser:
- Tracked grants
- Status updates
- Notes and documentation
- Nothing is sent to external servers
- Your data stays private and local

### 5. Export Capabilities
Export your grant portfolio in multiple formats:

**JSON Export** - Complete data backup
- All tracked grants with status
- All notes
- Timestamp of export
- Use for backup or migration

**CSV Export** - Excel-compatible spreadsheet
- Agency, Title, Amount, Deadline
- Current status
- Scope and link
- All notes
- Perfect for board reports

**Calendar Export (.ics)** - Deadline reminders
- Imports into Google Calendar, Outlook, Apple Calendar
- Creates events for all grant deadlines
- Includes grant details and links
- Never miss a deadline

---

## Database Overview

### Federal Sources (12 grants)
- Veterans Affairs Canada (2 programs)
- Canadian Institutes of Health Research
- Employment & Social Development Canada
- Public Health Agency of Canada
- Mental Health Commission of Canada

### Corporate/Foundation (25+ grants)
- Bell Let's Talk Community Fund
- RBC Foundation
- TD Bank Community Giving
- Google.org Impact Challenge
- True Patriot Love
- Wounded Warriors Canada
- Legion National Foundation
- Home Depot Canada Foundation
- Manulife, Scotiabank, Walmart, Costco
- Mastercard Foundation (large grants up to $5M)

### Provincial Sources (13+ grants)
- **Ontario**: Trillium Foundation (2 streams), Provincial Health Fund, CAMH
- **British Columbia**: Gaming Grants, Vancouver Foundation, BC Health
- **Alberta**: Community Initiatives Program, Calgary Foundation, Edmonton Foundation
- **Quebec**: Community Action Fund, Montreal Foundation
- **Nova Scotia**: Health Authority Innovation Fund, Community Foundation

### Veteran-Specific (7 grants)
- Veterans Affairs (multiple streams)
- Wounded Warriors Canada
- VETS Canada
- True Patriot Love
- Legion National Foundation
- Home Depot Foundation (veteran causes)

### Mental Health Focus (8 grants)
- Bell Let's Talk
- CAMH Foundation
- Mental Health Commission of Canada
- Jack.org (youth)
- Kids Help Phone
- RBC Mental Health & Wellness

---

## Grant Amount Ranges

- **Small Grants**: $1k - $25k (perfect for pilot programs)
- **Medium Grants**: $25k - $100k (program expansion)
- **Large Grants**: $100k - $500k (major initiatives)
- **Transformative**: $500k - $5M (multi-year partnerships)

The database includes all ranges to match your organization's stage and capacity.

---

## How to Use Effectively

### For New Organizations
1. Start with **small corporate grants** ($5k-$25k)
   - Bell Let's Talk
   - Canada Post Foundation
   - Walmart, Costco community grants
2. Track 5-10 grants in "Discovered" status
3. Research eligibility for each (mark as "Researching")
4. Apply to 2-3 to start building track record

### For Established Organizations
1. Search for **large federal/provincial grants** ($100k+)
   - VAC Well-being Fund
   - CIHR Operating Grants
   - OTF Grow Grants
2. Track 10-20 opportunities
3. Prioritize by deadline and fit
4. Prepare evergreen documents to speed up applications

### For Research-Focused Organizations
1. Filter for **research and innovation grants**
   - CIHR Mental Health stream
   - Wounded Warriors Research Fund
   - Mental Health Commission Innovation
   - Google.org Impact Challenge
2. Track grants requiring peer review separately
3. Build relationships with program officers

---

## Pro Tips

### Deadline Management
- Set **internal deadlines 2 weeks before** official deadlines
- Use the calendar export to sync with your team's calendar
- Check "rolling" grants quarterly - they can close unexpectedly

### Application Strategy
- **Track more than you apply** - Aim for 3:1 ratio (track 15, apply to 5)
- Use notes to document **why you didn't apply** (helps next year)
- Mark rejected applications with **lessons learned** in notes

### Building Relationships
- Add grant officer contact info to notes
- Document phone call insights
- Track past interactions for follow-up

### Data Management
- **Export to CSV monthly** for board reports
- **Export to JSON quarterly** for backup
- Share CSV with grant writing team for coordination

---

## Keyboard Shortcuts

While the interface is mouse-friendly, here are some navigation tips:
- **Tab** - Navigate between fields and buttons
- **Enter** - Activate buttons
- **Esc** - Close modals

---

## Browser Compatibility

Tested and optimized for:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

**Mobile Support**: Responsive design works on tablets and phones, though desktop recommended for heavy tracking work.

---

## Data Privacy & Security

### What's Stored Locally (in your browser):
- Grant IDs you've tracked
- Status updates you've made
- Notes you've written
- Export timestamps

### What's NOT Stored:
- Your organization name
- Contact information
- Financial data
- Application documents

### How to Clear Data:
1. Browser settings → Clear browsing data
2. Or: Console → `localStorage.clear()`

### How to Backup:
1. Export to JSON regularly
2. Save the JSON file to cloud storage
3. To restore: Import JSON feature (coming in v2.2)

---

## Troubleshooting

### "My tracked grants disappeared"
- Check if browser cleared localStorage
- Restore from last JSON export
- Prevention: Export weekly

### "Deadline shows as CLOSED but it's not"
- Date format might be incorrect in database
- Report issue with grant ID
- We'll update in next release

### "Export doesn't work"
- Check browser popup blocker
- Try different export format
- Ensure you have grants tracked

### "Can't find a specific grant"
- Try broader keywords
- Check jurisdiction filter (set to "All")
- Grant might not be in database yet (request addition)

---

## Requesting New Grants

Found a grant we don't have? Submit via:
1. GitHub issue (if technical)
2. Email with these details:
   - Grant name
   - Funding organization
   - Amount range
   - Deadline (or "rolling")
   - Link to application page
   - Tags (PTSD, Veterans, Mental Health, etc.)

We update the database monthly with community submissions.

---

## Version History

### v2.1 (Current) - November 2025
- Expanded database to 50+ grants
- Added tracking system with 6 status stages
- Implemented deadline calculation and urgency indicators
- Added notes system for each grant
- Built export system (JSON, CSV, Calendar)
- Added local storage persistence
- Improved UI with dual-tab navigation
- Enhanced filtering and search

### v2.0 - November 2025
- Initial tactical interface
- 10 verified grants
- Basic keyword search
- Deep search protocol (Google Dork)

---

## Roadmap (Future Versions)

### v2.2 - Collaboration Features
- Share grant lists via URL
- Team assignment (who's working on what)
- Import JSON data
- Comment threads on grants

### v2.3 - Document Management
- Application checklist builder
- Document vault (track what docs you have ready)
- Reusability scoring (which docs work for multiple grants)

### v3.0 - Intelligence Layer
- Smart matching algorithm (auto-score grant fit)
- Dashboard analytics
- Calendar view
- Email notifications for new grants
- Web scraping automation

---

## Support

For questions, issues, or feature requests:
- Check this guide first
- Review PROJECT_ANALYSIS.md for strategy details
- Submit issues via your preferred channel

---

## License & Credits

**Grant Recon v2.1**
Built for wounded warriors, veterans with PTSD, and the organizations that serve them.

Data sources: Public government websites, foundation portals, and community submissions.
Updated: November 2025

*Your mission: Secure the funding. Our mission: Make it easier.*

---

**◆ GRANT RECON - MISSION CONTROL**
