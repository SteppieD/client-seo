# SEO URLs and Meta Descriptions Template

This template provides the structure for generating SEO-optimized URLs and meta descriptions for all content pieces.

## Primary Pillar Page

**Topic:** Best {{PRIMARY_SERVICE}} in {{LOCATION}}
**Target Keyword:** {{PRIMARY_KEYWORD}}
**SEO URL:** `/best-{{PRIMARY_SERVICE_SLUG}}-in-{{LOCATION_SLUG}}`
**Meta Description:** "Discover the best {{PRIMARY_SERVICE}} in {{LOCATION}}. {{UNIQUE_VALUE_PROPOSITION}}. {{CALL_TO_ACTION}}."
**Character Count:** [150-160 characters]

## Secondary Pillar Pages

### {{SERVICE_TYPE_1}} Focused Page
**Topic:** {{SERVICE_TYPE_1}} in {{LOCATION}}
**Target Keyword:** {{SERVICE_1_KEYWORD}}
**SEO URL:** `/{{SERVICE_TYPE_1_SLUG}}-{{LOCATION_SLUG}}`
**Meta Description:** "{{SERVICE_TYPE_1}} in {{LOCATION}}. {{SERVICE_1_BENEFIT}}. {{SERVICE_1_CTA}}."

### {{SERVICE_TYPE_2}} Focused Page
**Topic:** {{SERVICE_TYPE_2}} in {{LOCATION}}
**Target Keyword:** {{SERVICE_2_KEYWORD}}
**SEO URL:** `/{{SERVICE_TYPE_2_SLUG}}-{{LOCATION_SLUG}}`
**Meta Description:** "{{SERVICE_TYPE_2}} in {{LOCATION}}. {{SERVICE_2_BENEFIT}}. {{SERVICE_2_CTA}}."

### {{SERVICE_TYPE_3}} Focused Page
**Topic:** {{SERVICE_TYPE_3}} in {{LOCATION}}
**Target Keyword:** {{SERVICE_3_KEYWORD}}
**SEO URL:** `/{{SERVICE_TYPE_3_SLUG}}-{{LOCATION_SLUG}}`
**Meta Description:** "{{SERVICE_TYPE_3}} in {{LOCATION}}. {{SERVICE_3_BENEFIT}}. {{SERVICE_3_CTA}}."

## Comparison Pages

### vs Competitor 1
**Topic:** {{BUSINESS_NAME}} vs {{COMPETITOR_1}}
**SEO URL:** `/{{BUSINESS_NAME_SLUG}}-vs-{{COMPETITOR_1_SLUG}}`
**Meta Description:** "{{BUSINESS_NAME}} vs {{COMPETITOR_1}}: Compare {{PRIMARY_SERVICE}} options in {{LOCATION}}. {{COMPARISON_BENEFIT}}."

### vs Competitor 2
**Topic:** {{BUSINESS_NAME}} vs {{COMPETITOR_2}}
**SEO URL:** `/{{BUSINESS_NAME_SLUG}}-vs-{{COMPETITOR_2_SLUG}}`
**Meta Description:** "{{BUSINESS_NAME}} vs {{COMPETITOR_2}}: Compare {{PRIMARY_SERVICE}} options in {{LOCATION}}. {{COMPARISON_BENEFIT}}."

## Location-Based Pages

### Nearby Attractions
**Topic:** {{PRIMARY_SERVICE}} Near {{LOCAL_ATTRACTION_1}}
**SEO URL:** `/{{PRIMARY_SERVICE_SLUG}}-near-{{ATTRACTION_1_SLUG}}`
**Meta Description:** "{{PRIMARY_SERVICE}} near {{LOCAL_ATTRACTION_1}}. {{LOCATION_BENEFIT}}. Book your stay today!"

## Seasonal/Activity Pages

### Peak Season
**Topic:** {{PEAK_SEASON}} {{PRIMARY_SERVICE}} in {{LOCATION}}
**SEO URL:** `/{{PEAK_SEASON_SLUG}}-{{PRIMARY_SERVICE_SLUG}}-{{LOCATION_SLUG}}`
**Meta Description:** "{{PEAK_SEASON}} {{PRIMARY_SERVICE}} in {{LOCATION}}. {{SEASONAL_BENEFIT}}. {{SEASONAL_CTA}}."

### Off Season
**Topic:** {{OFF_SEASON}} {{PRIMARY_SERVICE}} in {{LOCATION}}
**SEO URL:** `/{{OFF_SEASON_SLUG}}-{{PRIMARY_SERVICE_SLUG}}-{{LOCATION_SLUG}}`
**Meta Description:** "{{OFF_SEASON}} {{PRIMARY_SERVICE}} in {{LOCATION}}. {{OFF_SEASON_BENEFIT}}. {{OFF_SEASON_CTA}}."

## URL Slug Guidelines

### Variable to Slug Conversion:
- **{{PRIMARY_SERVICE_SLUG}}** = Convert {{PRIMARY_SERVICE}} to lowercase, replace spaces with hyphens
- **{{LOCATION_SLUG}}** = Convert {{LOCATION}} to lowercase, replace spaces with hyphens
- **{{BUSINESS_NAME_SLUG}}** = Convert {{BUSINESS_NAME}} to lowercase, replace spaces with hyphens

### Examples:
- "Mountain Lodge Accommodations" → `mountain-lodge-accommodations`
- "Whistler Village" → `whistler-village`
- "Sunrise Mountain Lodge" → `sunrise-mountain-lodge`

## Meta Description Guidelines

### Structure:
1. **Hook:** Start with target keyword
2. **Value:** Include unique benefit/differentiator
3. **Action:** End with compelling CTA

### Character Limits:
- **Minimum:** 150 characters
- **Maximum:** 160 characters
- **Optimal:** 155 characters

### Required Elements:
- Primary keyword
- Location (if local business)
- Unique value proposition
- Call to action
- Brand differentiation

### Examples:
- "Discover the best mountain lodges in Whistler. Authentic alpine experiences with private hot tubs. Book your mountain getaway today!" (159 chars)
- "Luxury ski-in ski-out accommodations in Whistler Village. Family-owned lodge with personalized service. Reserve your winter escape now!" (146 chars)

## Implementation Notes

### For WordPress/CMS:
- Use URL slug in permalink settings
- Add meta description to SEO plugin (Yoast, RankMath, etc.)
- Include schema markup for local business

### For Static Sites:
- Update HTML `<title>` tag with page title
- Add `<meta name="description" content="...">` tag
- Configure URL routing/rewrites

### Quality Check:
- Verify no duplicate URLs
- Ensure all meta descriptions are unique
- Check character counts
- Test URLs work and redirect properly
- Validate schema markup if used