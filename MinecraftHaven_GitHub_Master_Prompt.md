# MinecraftHaven — Complete AI Website Build Prompt

## PROJECT GOAL

Build a complete, professional, production-ready Minecraft information platform called **MinecraftHaven**.

This project must be a real working website, not merely a visual mockup or landing page.

The website should be designed as a long-term Minecraft knowledge hub containing a scalable database, guides, tools, search, AI-assistant integration architecture, update/news system, SEO, responsive UI, performance optimization, security, and free-hosting compatibility.

The website must be suitable for a student project and should have a free-first architecture.

---

# 1. CORE REQUIREMENTS

Build an actual working web application.

DO NOT:
- Create fake buttons that do nothing.
- Create navigation links that lead nowhere.
- Pretend an AI API is working when no API key is configured.
- Expose API keys or secrets in frontend code.
- Invent current Minecraft news or version compatibility.
- Copy another website's design.
- Use copyrighted Minecraft assets in a way that suggests official ownership.

DO:
- Use reusable components.
- Use a scalable content/data architecture.
- Make the public website work without paid services wherever possible.
- Keep optional paid/API functionality separate.
- Make the site lightweight.
- Make it excellent on Android and desktop.
- Include clear loading, empty, error, and 404 states.
- Make the project easy to deploy using GitHub and a free hosting platform.

---

# 2. BRAND

Name:

MinecraftHaven

Tagline:

"Your Ultimate Minecraft Knowledge Hub"

Purpose:

A comprehensive unofficial Minecraft information website covering gameplay knowledge, blocks, items, mobs, biomes, crafting, guides, commands, redstone, farming, building, add-ons, resource packs, tools, news, and an optional AI assistant.

The site should feel like a serious modern knowledge platform rather than an AI-generated template.

---

# 3. VISUAL DESIGN

Use a premium Minecraft-inspired dark interface.

Style:
- Dark/black base
- Subtle green/cyan accents
- Modern cards
- Clean typography
- Pixel/block-inspired visual details
- Strong contrast
- Rounded but not excessive corners
- Subtle shadows
- Smooth lightweight transitions
- Professional spacing
- Responsive layouts
- No unnecessary visual clutter

Avoid:
- Excessive animations
- Giant background videos
- Heavy 3D effects
- Fake Minecraft screenshots
- Generic AI-dashboard appearance

Create an original logo using a simple block-inspired symbol and the MinecraftHaven wordmark.

---

# 4. GLOBAL NAVIGATION

Create the following primary navigation:

- Home
- Database
- Blocks
- Items
- Mobs
- Biomes
- Dimensions
- Enchantments
- Potions
- Crafting
- Farming
- Building
- Redstone
- Commands
- Guides
- Add-ons
- Resource Packs
- Shaders
- News
- Tools
- AI Assistant
- About

Add a responsive mobile menu.

Add a global search button/bar available throughout the site.

---

# 5. HOMEPAGE

Create a highly polished homepage.

Hero:

Title:
"Everything Minecraft. One Place."

Subtitle:
"Explore Minecraft knowledge, guides, tools, recipes, commands, and more."

Large search box:

"Search blocks, mobs, items, guides, commands..."

Quick-access cards:

- Blocks
- Items
- Mobs
- Biomes
- Crafting
- Enchantments
- Potions
- Commands
- Redstone
- Farming

Add:

- Featured guides
- Popular database entries
- Latest verified updates
- Popular searches
- Minecraft tools
- Beginner section
- Advanced section
- AI Assistant section
- Recently viewed content
- Recommended guides

Add a visible unofficial-project disclaimer.

---

# 6. GLOBAL SEARCH

Build a real search system.

Search across:

- Blocks
- Items
- Mobs
- Biomes
- Dimensions
- Recipes
- Enchantments
- Potions
- Commands
- Guides
- Add-ons
- Resource Packs
- Shaders
- News

Features:

- Instant search suggestions
- Search categories
- Filters
- Tags
- Search result ranking
- Empty state
- Recent searches using local storage
- Keyboard navigation
- Mobile-friendly interface
- Search URL/query support

Example:

Searching "diamond" should find:

- Diamond
- Diamond Ore
- Deepslate Diamond Ore
- Diamond Pickaxe
- Diamond Sword
- Diamond Armor
- Diamond-related recipes
- Diamond guides

Use debounced search to avoid unnecessary processing.

---

# 7. DATABASE ARCHITECTURE

Create reusable database models and components.

Every database entry should support:

- Name
- Slug
- Category
- Description
- Long description
- Edition
- Minecraft version
- Compatibility
- Obtaining method
- Uses
- Recipe
- Drops
- Mining information
- Tool requirement
- Rarity
- Tags
- Search keywords
- Related entries
- Images/media
- Last verified date
- Source/reference

Create reusable detail-page templates.

---

# 8. BLOCK DATABASE

Create a Blocks section.

Categories:

- Natural
- Building
- Decoration
- Redstone
- Functional
- Utility
- Nether
- End
- Ores
- Wood
- Stone
- Other

Representative entries:

- Stone
- Dirt
- Grass Block
- Diamond Ore
- Deepslate
- Obsidian
- Ancient Debris
- Netherite Block
- Redstone Ore
- Emerald Ore

Do not claim the sample data represents a complete current database.

Make the architecture capable of thousands of entries.

---

# 9. ITEM DATABASE

Create an Items section.

Categories:

- Materials
- Tools
- Weapons
- Armor
- Food
- Utility
- Transportation
- Brewing
- Redstone
- Other

Example entries:

- Diamond
- Netherite Ingot
- Iron Ingot
- Gold Ingot
- Emerald
- Stick
- Torch
- Food
- Tools
- Weapons
- Armor

---

# 10. MOB DATABASE

Create:

- Passive mobs
- Neutral mobs
- Hostile mobs
- Bosses

Each mob page should support:

- Health
- Damage
- Drops
- Spawn conditions
- Biomes
- Behavior
- Breeding
- Variants
- Related guides
- Edition/version compatibility

Never invent numerical stats if they have not been verified.

---

# 11. BIOME DATABASE

Create a biome explorer.

Categories:

Overworld:
- Plains
- Forest
- Taiga
- Desert
- Jungle
- Savanna
- Mountains
- Swamp
- Ocean
- Snowy regions
- Other biomes

Nether:
- Nether Wastes
- Soul Sand Valley
- Crimson Forest
- Warped Forest
- Basalt Deltas

End-related environments where applicable.

Each biome page should support:

- Description
- Climate information
- Terrain
- Mobs
- Structures
- Resources
- Related blocks
- Related guides
- Edition/version

---

# 12. DIMENSIONS

Create:

- Overworld
- Nether
- End

Include:

- Environment
- Travel information
- Important structures
- Mobs
- Resources
- Survival tips
- Related guides

---

# 13. CRAFTING DATABASE

Create a crafting system.

Users should be able to:

1. Search an item.
2. Open its recipe.
3. See the crafting grid.
4. See required materials.
5. See output quantity.
6. See related recipes.

Categories:

- Tools
- Weapons
- Armor
- Blocks
- Food
- Redstone
- Transportation
- Decoration
- Utility

Add:

- Copy/share functionality where useful
- Recipe cards
- Related recipes

---

# 14. ENCHANTMENT DATABASE

Create an enchantment section.

Each enchantment should support:

- Name
- Description
- Maximum level
- Applicable items
- Compatibility
- Conflicts
- How to obtain
- Recommended use cases
- Related guides
- Edition/version

Add an enchantment comparison tool.

Do not give unsupported claims such as "best enchantment" as a factual statement.

---

# 15. POTION DATABASE

Create:

- Potion database
- Brewing recipes
- Ingredients
- Effects
- Durations
- Strength levels
- Related items
- Brewing guide

Build a visual step-by-step brewing interface.

---

# 16. REDSTONE

Create a dedicated Redstone section.

Categories:

- Beginner
- Intermediate
- Advanced

Guides can include:

- Automatic farms
- Doors
- Elevators
- Storage systems
- Redstone clocks
- Mob farms
- XP farms
- Sorting systems
- Hidden entrances
- Redstone mechanisms

Each guide supports:

- Difficulty
- Materials
- Steps
- Build time
- Version compatibility
- Images/diagrams
- Troubleshooting
- Related guides

---

# 17. FARM DATABASE

Create farm guides for:

- Iron
- Food
- Wheat
- Sugar Cane
- Bamboo
- Wood
- XP
- Mob drops
- Gold
- Other resources

Each farm guide supports:

- Materials
- Build steps
- Difficulty
- Efficiency information
- Space requirements
- Version compatibility
- Troubleshooting
- Notes

Do not claim a farm works on a particular version unless verified.

---

# 18. BUILDING SECTION

Create:

- Starter houses
- Modern builds
- Medieval builds
- Castles
- Villages
- Bridges
- Towers
- Underground bases
- Storage rooms
- Survival bases

Each guide supports:

- Materials
- Difficulty
- Step-by-step instructions
- Design tips
- Related builds
- Version notes

---

# 19. COMMAND CENTER

Create a searchable command library.

Categories:

- Teleportation
- Gamemode
- Weather
- Time
- Effects
- Summoning
- Give
- Clear
- Locate
- Fill
- Clone
- Execute
- Scoreboard
- Particles
- World management

Each command page supports:

- Syntax
- Arguments
- Example
- Explanation
- Edition
- Version
- Common mistakes
- Copy button

Clearly distinguish Java and Bedrock syntax.

---

# 20. TOOLS

Create browser-based tools that work without a paid backend where possible.

Include:

- Nether portal calculator
- Coordinate converter
- Stack calculator
- XP calculator
- Enchantment helper
- Potion helper
- Time/day calculator
- Block conversion calculator
- Mining-efficiency helper
- Text/color formatter where appropriate
- Command helper

Tools should have:

- Input validation
- Clear results
- Reset button
- Mobile-friendly UI
- Helpful explanations
- No unnecessary server requests

---

# 21. AI MINECRAFT ASSISTANT

Create an AI Assistant page.

Title:

"Ask MinecraftHaven AI"

Example questions:

- How do I make an iron farm?
- How do I find diamonds?
- What should I take to the Nether?
- Explain Fortune.
- Give me a starter house plan.
- Explain this Minecraft command.

Architecture requirements:

- Create a secure API integration point.
- Never expose an API key in frontend code.
- Use environment variables.
- Use a server-side/API route for secrets.
- If no AI API key exists, show a setup message rather than pretending the AI works.
- Add rate limiting architecture.
- Add basic input-length limits.
- Do not store conversations unless the user explicitly enables it.

The core website must remain usable without the AI service.

---

# 22. GUIDES

Create a professional article system.

Categories:

- Beginner
- Survival
- Building
- Redstone
- Farming
- Mining
- Nether
- End
- Enchanting
- Combat
- Commands
- Multiplayer
- Add-ons

Article structure:

- Title
- Summary
- Difficulty
- Reading time
- Table of contents
- Step-by-step sections
- Images
- Tips
- Warnings
- Related guides
- Tags
- Last updated date
- Sources when appropriate

---

# 23. ADD-ONS / MODS

Create separate sections:

- Bedrock Add-ons
- Java Mods
- Resource Packs
- Shaders

Each listing supports:

- Name
- Description
- Edition
- Version compatibility
- Category
- Author
- Original source
- Installation instructions
- Screenshots
- Last updated
- Tags

Never claim compatibility without verification.

Never host third-party files unless legally permitted.

Prefer linking users to the original creator/source.

Add warning:

"Always check the original creator's page and current version compatibility before installing third-party files."

---

# 24. NEWS & UPDATES

Create:

- Minecraft Updates
- Bedrock Updates
- Java Updates
- Community News
- MinecraftHaven Updates

Each article:

- Title
- Date
- Summary
- Full article
- Source
- Related version
- Tags

Do not invent current Minecraft news.

If no current data source is connected, clearly label content as sample/demo content.

---

# 25. VERSION SYSTEM

Design the database around version compatibility.

Every relevant entry supports:

- Edition
- Version
- Compatibility
- Last verified date

Filters:

- Java
- Bedrock
- All

Create a version selector.

The architecture should allow new versions to be added without rebuilding every page.

---

# 26. USER FEATURES

Optional client-side features:

- Favorites
- Recently viewed
- Reading history
- Saved guides

Use browser local storage where possible.

Do not collect unnecessary personal information.

If authentication is added later, make it optional.

---

# 27. ADMIN / CONTENT ARCHITECTURE

Create a clean data/content structure that allows adding:

- Blocks
- Items
- Mobs
- Biomes
- Recipes
- Enchantments
- Potions
- Commands
- Guides
- Add-ons
- Resource Packs
- Shaders
- News
- Versions
- Tools

Do not hard-code every page separately.

Use reusable schemas and components.

If a CMS is not required, use structured local data files such as JSON/Markdown/MDX or another appropriate content format.

---

# 28. SEO

Implement strong technical SEO.

Include:

- Unique title tags
- Meta descriptions
- Canonical URLs
- Open Graph metadata
- Social sharing metadata
- Structured data where appropriate
- Semantic HTML
- Breadcrumbs
- Internal linking
- Sitemap
- robots.txt
- Descriptive alt text
- Clean URLs

Examples:

/blocks/diamond-ore
/items/diamond
/mobs/creeper
/biomes/plains
/guides/how-to-find-diamonds
/commands/tp
/tools/nether-portal-calculator

Do not keyword-stuff.

Create useful content for humans first.

---

# 29. PERFORMANCE

Optimize heavily for:

- Android
- Low-end devices
- Slow networks
- Desktop

Use:

- Lazy loading
- Responsive images
- Image compression
- Code splitting
- Minimal JavaScript
- Static generation where appropriate
- Caching
- Pagination
- Efficient search
- No unnecessary libraries
- No giant background videos
- Limited animation

The homepage should load quickly.

---

# 30. MOBILE DESIGN

Make mobile a first-class experience.

Support:

- 360px
- 390px
- 412px
- 768px
- 1024px
- 1440px+

Mobile requirements:

- Compact navigation
- Large touch targets
- Readable text
- Responsive cards
- Fast search
- Collapsible sections
- No horizontal overflow
- Sticky controls only where useful

---

# 31. ACCESSIBILITY

Implement:

- Keyboard navigation
- Visible focus states
- Semantic headings
- Accessible buttons
- Proper form labels
- Good contrast
- Alt text
- Screen-reader-friendly controls
- Reduced-motion support

---

# 32. SECURITY

Implement:

- Input validation
- Output sanitization
- Secure API architecture
- Environment variables for secrets
- No credentials in Git
- Safe error messages
- Dependency hygiene
- Security headers where supported
- Rate limiting architecture for public API endpoints

Create a .gitignore that prevents secrets and build artifacts from being committed.

Never place:

API keys
Passwords
Database credentials
Private tokens

inside frontend source code.

---

# 33. MONETIZATION-READY DESIGN

Do not make the initial website spammy.

Create reserved responsive areas for:

- Advertisements
- Affiliate recommendations
- Sponsored content

Use placeholders.

Do not create fake ads.

Prepare optional integration points for:

- Analytics
- Search Console
- Affiliate links

Do not make monetization a requirement for the website to function.

---

# 34. AUTOMATIC UPDATE ARCHITECTURE

Prepare the architecture for future automated content updates.

Possible sources:

- Official/authorized APIs
- Public feeds
- Maintained datasets
- Manually verified sources

Do not:

- Aggressively scrape websites
- Bypass robots.txt
- Bypass authentication
- Bypass paywalls
- Bypass rate limits
- Copy copyrighted content wholesale

Imported information should retain:

- Source
- Date
- Version
- Last verified date

Create an admin "Update Status" concept.

---

# 35. DATA QUALITY

For factual Minecraft information:

- Prefer authoritative/official sources where available.
- Record source/reference information.
- Record version compatibility.
- Record last verified date.
- Avoid presenting uncertain information as fact.
- Avoid duplicate entries.
- Provide a way to correct outdated content later.

Create a data-validation structure where practical.

---

# 36. LEGAL / ABOUT PAGE

Create an About page with this meaning:

"MinecraftHaven is an unofficial fan-created Minecraft information website."

"Minecraft is a trademark of Mojang Studios/Microsoft."

"MinecraftHaven is not affiliated with, endorsed by, or sponsored by Mojang Studios or Microsoft."

"Third-party resources remain the property of their respective creators."

Respect licenses and terms of original creators.

---

# 37. ERROR HANDLING

Create professional states for:

- 404
- Search with no results
- Missing database entry
- Network error
- API unavailable
- Loading
- Empty content
- Invalid form input

Never show a blank broken page.

---

# 38. DESIGN SYSTEM

Create reusable components for:

- Header
- Footer
- Navigation
- Search
- Cards
- Database cards
- Article cards
- Breadcrumbs
- Tabs
- Filters
- Modals
- Toasts
- Buttons
- Inputs
- Tables
- Recipe grids
- Tool panels
- Loading skeletons
- Error states
- Empty states

Maintain consistent spacing, typography, and responsive behavior.

---

# 39. ROUTING

Create real routes for all major sections.

At minimum:

/
 /database
 /blocks
 /items
 /mobs
 /biomes
 /dimensions
 /enchantments
 /potions
 /crafting
 /farming
 /building
 /redstone
 /commands
 /guides
 /addons
 /resource-packs
 /shaders
 /news
 /tools
 /ai
 /about

Use dynamic routes for database entries.

Examples:

/blocks/[slug]
/items/[slug]
/mobs/[slug]
/biomes/[slug]
/guides/[slug]
/commands/[slug]
/tools/[slug]

---

# 40. SAMPLE DATA

Include enough clearly labeled demo/sample data to make the site look complete during development.

Include representative entries for:

- Blocks
- Items
- Mobs
- Biomes
- Recipes
- Enchantments
- Potions
- Commands
- Guides
- Tools

Clearly mark unverified/demo content where necessary.

Do not imply that sample data is a complete current Minecraft database.

---

# 41. CONTENT SCALE

The architecture should be capable of handling:

- Hundreds of categories
- Thousands of database entries
- Thousands of guides
- Large search indexes
- Multiple Minecraft editions
- Multiple versions

Do not create thousands of duplicate source files just to demonstrate scale.

Use templates and structured data.

---

# 42. FREE-FIRST ARCHITECTURE

The base site should be deployable on free infrastructure.

Preferred architecture:

Frontend:
A modern framework suitable for static/edge deployment.

Content:
Static JSON/Markdown/MDX or another lightweight structured format.

Optional backend:
Serverless API routes.

Optional database:
A free-tier database only when necessary.

Optional AI:
External AI API connected securely through a server-side route.

Do not make a paid database mandatory.

Do not make a paid server mandatory.

---

# 43. GITHUB READINESS

Create:

README.md
.gitignore
LICENSE or project-license placeholder
.env.example

The README must explain:

1. Project overview
2. Technology stack
3. Folder structure
4. Local installation
5. Development command
6. Production build
7. Environment variables
8. AI configuration
9. Content editing
10. Adding database entries
11. Adding guides
12. Deployment
13. Free Cloudflare Pages deployment
14. Free Netlify deployment
15. Free Vercel deployment
16. Troubleshooting
17. Updating dependencies

Never put real API keys into .env.example.

Use placeholders such as:

AI_API_KEY=your_key_here

---

# 44. FREE DEPLOYMENT

Design the project so it can be deployed from GitHub to a free hosting provider such as:

- Cloudflare Pages
- GitHub Pages where compatible
- Netlify
- Vercel

The core static/public site should not require a credit card.

If a feature cannot work on static hosting, isolate it as an optional serverless feature.

Explain deployment clearly in README.md.

---

# 45. AUTOMATED TESTING

Add basic tests where practical.

Test:

- Search
- Routing
- Core tools
- Data loading
- Important UI components
- Error states

Also perform a build check.

Before declaring completion:

- Run the production build.
- Fix build errors.
- Check for console errors.
- Check broken routes.
- Check responsive layouts.
- Check missing assets.
- Check exposed secrets.
- Check search functionality.
- Check 404 behavior.

---

# 46. QUALITY CONTROL

Before finishing the implementation, verify:

NAVIGATION
- Every navigation link works.

SEARCH
- Search works.
- Search suggestions work.
- Empty results work.

DATABASE
- Entries open.
- Dynamic routes work.
- Related content works.

TOOLS
- Tools calculate correctly.
- Invalid inputs are handled.

MOBILE
- No horizontal overflow.
- Navigation works.
- Text remains readable.

SEO
- Metadata exists.
- Canonicals are handled.
- Sitemap/robots architecture exists.

SECURITY
- No secrets committed.
- User input is validated.
- API keys are server-side only.

PERFORMANCE
- Images are optimized.
- Heavy dependencies are avoided.
- Pages are not unnecessarily large.

---

# 47. IMPORTANT AI-BUILDER BEHAVIOR

If you are an AI coding agent, do not stop after creating the homepage.

Continue implementing the actual project structure.

Work in phases if necessary:

PHASE 1:
- Core layout
- Routing
- Homepage
- Search
- Database architecture

PHASE 2:
- Blocks
- Items
- Mobs
- Biomes
- Crafting
- Enchantments
- Potions

PHASE 3:
- Guides
- Building
- Farming
- Redstone
- Commands

PHASE 4:
- Add-ons
- Resource Packs
- Shaders
- News

PHASE 5:
- Tools
- AI integration architecture
- SEO
- Performance
- Security

PHASE 6:
- Testing
- Deployment documentation
- Final cleanup

Do not remove working functionality while adding later phases.

---

# 48. FINAL RESULT

The final result should be a professional, scalable Minecraft knowledge platform that can start as a free student project and grow over time.

It should be:

- Fast
- Responsive
- Secure
- Searchable
- SEO-friendly
- Easy to update
- Easy to deploy
- Free-first
- Mobile-friendly
- Accessible
- Scalable
- Professional

Most importantly:

BUILD THE ACTUAL WEBSITE.

Do not merely describe what the website could contain.

Create the working project files, components, routes, data structures, styles, tools, search, sample content, documentation, and deployment configuration.

When a feature depends on an external paid API, create the integration architecture and a safe fallback instead of making the entire website dependent on it.
