# Portfolio Sorting System

Your Jekyll site now has a flexible portfolio sorting system with three options:

## Sorting Methods

### 1. Manual Order (Default)
- Uses the `order` field in each portfolio's front matter
- Lower numbers appear first (1, 2, 3, etc.)
- Best for complete control over portfolio order

### 2. Date-based Sorting  
- Uses the `date` field in each portfolio's front matter
- Newest portfolios appear first (reverse chronological)
- Great for showing your latest work first

### 3. Alphabetical Sorting
- Uses the `title` field in each portfolio's front matter
- Sorts A-Z by portfolio title
- Simple and predictable ordering

## Current Portfolio Order (by order field):

1. **Basketball** (order: 1, date: 2025-06-01)
2. **Nature** (order: 2, date: 2025-05-15)  
3. **People** (order: 3, date: 2025-04-20)
4. **Sports** (order: 4, date: 2025-04-01)
5. **Studio** (order: 5, date: 2025-03-30)
6. **Wedding** (order: 6, date: 2025-03-15)

## How to Change Sorting Method

Edit `_config.yml` and change the `portfolio_sort_by` value:

```yaml
# Portfolio sorting options: "order", "date", or "title"
portfolio_sort_by: "order"    # Manual order (default)
# portfolio_sort_by: "date"   # Date-based (newest first)
# portfolio_sort_by: "title"  # Alphabetical by title
```

## How to Reorder Portfolios

### Manual Order Method:
1. Edit each portfolio file's front matter
2. Change the `order` number (lower = appears first)
3. Save and rebuild your site

### Date-based Method:
1. Edit each portfolio file's front matter  
2. Update the `date` field (YYYY-MM-DD format)
3. Newer dates will appear first

### Example Front Matter:
```yaml
---
layout: portfolio-item
image: /assets/images/portfolios/nature/thumbnail.jpg
category: Photography
order: 2
date: 2025-05-15
title: Nature
---
```

## Adding New Portfolios

1. Use the template in `_portfolios/_portfolios template/portfolio-template.html`
2. Replace `[FOLDER_NAME]`, `[NUMBER]`, `[YYYY-MM-DD]`, and `[PORTFOLIO_TITLE]` with your values
3. Choose an appropriate `order` number and `date`
4. Add your images to `/assets/images/portfolios/[FOLDER_NAME]/`

## Tips

- **Manual Order**: Leave gaps between numbers (1, 5, 10, 15) so you can easily insert new portfolios later
- **Dates**: Use the actual date you completed/published the portfolio work
- **Titles**: Keep them concise and descriptive for alphabetical sorting
- Remember to restart your Jekyll server after changing `_config.yml`
