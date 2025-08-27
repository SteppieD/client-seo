# Claude Code Automatic Setup Guide

This file tells Claude Code how to automatically set up your complete SEO framework by asking you questions and analyzing your competitors.

---

## Instructions for Claude Code:

When a user asks you to set up their SEO framework, follow this process:

### STEP 1: GATHER BUSINESS INFORMATION
Ask the user these questions one at a time:

```
Hi! I'm going to set up a complete SEO content framework for you. I'll ask a few questions, then analyze your competitors and create everything automatically.

First, let me get your business information:

1. What's your business name?
2. What's your website URL?
3. What city/region do you serve?
4. What industry are you in? (brief description of what you do)
5. Who are your target customers?
6. What are your main services/products?
7. What makes you different from competitors? (key advantages)
8. Any other important business info I should know?
```

### STEP 2: GET COMPETITOR INTELLIGENCE  
Ask for competitor analysis:

```
Now I need to analyze your competition:

1. What's the URL of your top competitor's best guide/pillar page?
   (Look for their "Best [service] in [city]" or comprehensive guide)

2. [OPTIONAL] Any other competitor pillar pages you'd like me to analyze?
   (Up to 2-3 more URLs)

3. Who do you consider your main competitors? (business names)
```

### STEP 3: DETECT AND CONFIRM NICHE
Based on their answers:

```
Based on your business info, I've detected your niche as: [DETECTED_NICHE]

Is this correct? If not, how would you describe your specific niche?
```

### STEP 4: SET UP VARIABLES
Create these variables from their answers:

```
{BUSINESS_NAME} = [Their business name]
{WEBSITE_URL} = [Their website]
{LOCATION} = [Their city/region]  
{NICHE} = [Confirmed niche]
{INDUSTRY} = [Their industry]
{TARGET_CUSTOMERS} = [Their target customers]
{MAIN_SERVICES} = [Their services/products]
{KEY_DIFFERENTIATORS} = [Their advantages]
{REGION} = [Broader geographic area]
{CONTACT_INFO} = [Contact details if provided]
```

### STEP 5: ANALYZE COMPETITORS
For each competitor URL they provided:

1. **Use WebFetch to analyze the content**
2. **Document structure, tone, content types, links**
3. **Extract SEO elements and keyword usage**
4. **Note best practices to replicate**
5. **Identify content gaps and opportunities**

### STEP 6: CONDUCT NICHE RESEARCH
Use WebSearch to research:
- {NICHE} industry trends
- Common customer pain points in {NICHE}
- Content formats that work well in {INDUSTRY}
- SEO opportunities for {LOCATION} + {NICHE}

### STEP 7: CREATE COMPLETE FILE SYSTEM
Create these files using the variables and research:

#### Core Framework:
- **README.md** - Customized overview for {BUSINESS_NAME}
- **BUSINESS-PROFILE.md** - Complete business information using all variables
- **COMPETITOR-ANALYSIS.md** - Detailed analysis of fetched competitor content
- **NICHE-RESEARCH.md** - Industry insights and opportunities for {NICHE}
- **CONTENT-STRATEGY.md** - Strategic approach for {BUSINESS_NAME}

#### Templates & Guidelines:
- **PILLAR-PAGE-TEMPLATE.md** - Master template with {BUSINESS_NAME} variables
- **CONTENT-GUIDELINES.md** - Writing standards based on competitor analysis
- **QUALITY-CHECKLIST.md** - Pre-publication checklist for {NICHE}
- **LINK-STRATEGY.md** - Linking approach for {WEBSITE_URL}

#### Ready-to-Use Content:
- **pillar-page-draft-1.md** - Complete first pillar page ready to publish
- **content-ideas-list.md** - 20 future topics for {BUSINESS_NAME}
- **keyword-research.md** - Target keywords for {LOCATION} + {NICHE}

#### Implementation:
- **SETUP-INSTRUCTIONS.md** - How to implement everything
- **NEXT-STEPS.md** - 90-day action plan
- **TRACKING-METRICS.md** - What to measure

### STEP 8: CUSTOMIZATION REQUIREMENTS
For every file:
1. Replace ALL generic examples with {BUSINESS_NAME} specifics
2. Reference competitor insights throughout
3. Use {LOCATION}, {NICHE}, {TARGET_CUSTOMERS} context consistently
4. Include actual business differentiators and services
5. Create content that can compete with analyzed competitors

### STEP 9: FINAL DELIVERY
Tell the user:

```
✅ Complete! I've created your entire SEO framework:

CREATED FILES:
- [List all files created]

COMPETITOR ANALYSIS:
- Analyzed [X] competitor pages
- Identified [key insights]
- Found [content opportunities]

NEXT STEPS:
1. Review your BUSINESS-PROFILE.md
2. Check the competitor analysis
3. Read your first pillar page draft
4. Follow SETUP-INSTRUCTIONS.md to implement

Your system is ready to start creating high-quality SEO content that can compete in the {NICHE} market!
```

### IMPORTANT NOTES FOR CLAUDE CODE:
- **Use WebFetch** to analyze competitor URLs provided
- **Use WebSearch** for niche research and trends
- **Use the variable system consistently** across all files
- **Base everything on actual analysis**, not assumptions
- **Make content immediately actionable**
- **Focus on authentic differentiation**

### ERROR HANDLING:
- If competitor URLs don't work, ask for alternatives
- If niche detection is unclear, ask for clarification
- If business info is incomplete, ask follow-up questions
- Always confirm before proceeding with file creation

---

## For Users:

Simply tell Claude Code: **"Set up my SEO framework"** and it will guide you through this entire process automatically, creating a complete professional system customized for your business.

No prompts to copy, no files to figure out - just answer the questions and get everything created for you!