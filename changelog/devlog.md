# Development Log

## May 17, 2026

### Canary Upgrade and Website Setup

* Updated the OT server from an older protocol version to OpenTibiaBR Canary 14.x.
* Fixed multiple MyAAC compatibility issues during the migration process.
* Configured Apache/XAMPP and MySQL environment for website and account support.
* Organized backups and cleaned up local project files.
* Continued preparing the server for future online testing.

---

## May 18, 2026

### Gift Shop and Image System

* Fixed issues preventing the MyAAC gift shop system from properly delivering items.
* Configured item image support and animated item rendering.
* Corrected missing mount, addon, and item image issues.
* Added support for animated shop images and cosmetic previews.
* Continued improving overall webshop functionality.

---

## May 20, 2026

### Custom Content Development

* Continued learning the Tibia 14 appearances.dat workflow.
* Learned the difference between exporting object data and compiling appearances.dat.
* Gained experience using Assets Editor for item customization.
* Resolved client crashes caused by invalid appearance metadata.
* Successfully created and tested custom equipment.
* Verified custom items could be spawned, equipped, and delivered through the webshop.

---

## May 22, 2026

### Gameplay Modifications

* Modified experience rates and gameplay settings.
* Removed Yalahar travel quest requirements from boat captains.
* Tested gameplay adjustments and quality-of-life improvements.
* Began planning future event systems and VIP features.

---

## May 25, 2026

### Website Customization

* Updated Discord integration and invite links.
* Customized website wording and labels.
* Changed "View Highscore" to "View Highscores."
* Continued improving overall MyAAC website presentation and branding.

### Client Configuration

* Located the active MyAAC download client source page.
* Traced client version configuration through MyAAC files.
* Updated displayed client version information to 14.05.
* Added 14.05 support inside client configuration files.
* Updated download links and client references.

### Additional Notes

* Current Canary client package still requires navigating to the /bin folder to launch the client executable.
* Future goal is packaging a cleaner standalone BizzyOT client download for public players.

---

## May 30, 2026

### Donation System Updates

* Located and modified the active MyAAC donation template.
* Replaced Portuguese donation button text with English wording.
* Resolved Twig template caching issues while troubleshooting website updates.
* Enabled localhost donation testing through configuration changes.
* Improved donation page wording and usability.
* Began planning future payment integration.

### Shop System Expansion

* Expanded the webshop with additional equipment and progression items.
* Continued balancing donation point pricing and reward values.
* Improved shop organization and item categorization.
* Began planning vocation-based shop sections.
* Evaluating future mount, addon, and cosmetic categories.

### Website Improvements

* Continued improving English localization throughout the website.
* Updated various labels and interface text.
* Continued refining the player-facing website experience.

---

## Lessons Learned

* Modern Canary asset editing is significantly different from older OT item editing.
* The appearances.dat pipeline requires careful compilation and testing.
* Proper backups are critical before modifying client appearance data.
* Website customization often requires tracing configuration files, templates, and cached content.
* Debugging and troubleshooting large codebases takes patience and iterative testing.

---

## Current Focus

* Fixing remaining missing item images.
* Expanding webshop categories.
* Preparing payment integration.
* Improving website appearance and functionality.
* Planning mount and addon support.
* Preparing for player testing.

---

## Future Plans

* Implement donation payment processing.
* Continue expanding webshop functionality.
* Conduct closed testing with friends and family.
* Prepare hosting and VPS deployment.
* Improve server security and backup procedures.
* Develop custom event systems.
* Build and manage a player community.
* Continue long-term server support and updates.
