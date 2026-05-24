# Development Log

## May 2026

### Canary Upgrade and Website Setup
- Updated the OT server from an older protocol version to Canary 14.x.
- Fixed multiple MyAAC compatibility issues during the migration process.
- Configured Apache/XAMPP and MySQL environment for website and account support.
- Organized backups and cleaned up local project folder structure.

### Gift Shop and Image System
- Fixed issues preventing the MyAAC gift shop system from properly delivering items.
- Configured item image support and animated item rendering on the website.
- Corrected missing mount, addon, and item image problems.
- Added support for animated shop images for items and cosmetics.

### Custom VIP Item Development
- Spent significant time learning the Tibia 14 appearances.dat workflow.
- Learned the difference between exporting object data and compiling the full appearances.dat.
- Successfully duplicated and customized soft boots using Assets Editor.
- Resolved client crashes caused by invalid appearance metadata.
- Successfully created custom VIP boots that can:
  - be spawned in-game
  - be equipped by players
  - be delivered through the MyAAC gift shop

### Gameplay Modifications
- Modified experience rates and gameplay settings.
- Removed Yalahar travel quest requirements from boat captains.
- Began planning custom events and VIP gameplay systems.

## Lessons Learned
- Modern Canary asset editing is significantly different from older OT item editing.
- The appearances.dat pipeline requires careful compile and testing procedures.
- Proper backups are critical before modifying client appearance data.
- Debugging and troubleshooting large codebases takes patience and iterative testing.

## Current Focus
- Balancing VIP item regeneration values
- Creating additional VIP items
- Expanding event systems
- Improving website appearance and functionality
- Preparing payment and donation integration

## Future Plans
- Public hosting and VPS deployment
- Security hardening and backups
- Custom event systems
- Community management and player testing
- Long-term live server support
