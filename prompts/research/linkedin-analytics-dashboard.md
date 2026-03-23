# LinkedIn Analytics Dashboard


---

You are a LinkedIn growth strategist. I've uploaded my LinkedIn Analytics export. Analyze every sheet in this file and build me a complete profile audit with strategic recommendations.

## Step 1: Data Extraction

Read all sheets in my export file. These will include:
- DISCOVERY (overall impressions and reach)
- ENGAGEMENT (daily impressions and engagements over time)
- TOP POSTS (top 50 posts ranked by engagements AND by impressions)
- FOLLOWERS (daily new followers + total count)
- DEMOGRAPHICS (job titles, locations, industries, seniority, company size, top companies)

Parse all data. Clean any messy headers. Merge the two TOP POSTS tables (by engagements and by impressions) into one unified dataset per post.

## Step 2: Build an Interactive Dashboard

Create a single React artifact that visualizes my profile data as a dark-themed analytics dashboard. Include these panels:

1. HEADLINE METRICS (top row cards):
   - Total impressions, total reach, total new followers, avg daily impressions, avg daily engagements, avg engagement rate (engagements/impressions), total posts tracked

2. ENGAGEMENT TREND (line chart):
   - Daily impressions and engagements over the full date range
   - Use two y-axes (impressions on left, engagements on right)
   - Highlight the top 3 spike days with markers

3. FOLLOWER GROWTH (area chart):
   - Daily new followers over time
   - Include a 7-day moving average trendline
   - Show cumulative follower gain

4. POST PERFORMANCE SCATTER:
   - Plot each post with impressions (x-axis) vs engagements (y-axis)
   - Color-code posts into quadrants: high reach + high engagement (stars), high reach + low engagement (viral but shallow), low reach + high engagement (niche gold), low reach + low engagement (underperformers)
   - Make dots clickable or hoverable to show post URL and date

5. DAY-OF-WEEK HEATMAP:
   - Average impressions and engagements by day of the week
   - Show which days consistently perform best

6. AUDIENCE BREAKDOWN (bar charts):
   - Job titles distribution
   - Industries distribution  
   - Seniority levels distribution
   - Company size distribution
   - Top locations

Use Recharts. Make the dashboard responsive. Use a dark background (#0f1117) with accent colors. Add proper number formatting (67K not 67000). Include my total follower count prominently.

## Step 3: Strategic Analysis (written below the dashboard)

After the dashboard, provide a written analysis covering:

### Performance Summary
- What do the numbers tell me about my current trajectory?
- Am I growing, plateauing, or declining? Use the trendlines to answer.
- What is my engagement rate and how does it compare to LinkedIn benchmarks for accounts my size?

### Top Post Patterns
- Analyze my top 10 posts by impressions AND my top 10 by engagements
- What patterns emerge? (posting day, time of month, content themes if visible from URLs/dates)
- Which posts had high impressions but low engagement? What does that signal?
- Which posts had high engagement but lower impressions? What does that signal?

### Audience-Content Fit
- Based on my demographics, who is my core audience?
- What content topics and formats would resonate most with this audience profile?
- Are there audience segments I'm attracting that I should lean into or away from?

### Growth Velocity
- Calculate my average daily follower growth
- Project where I'll be in 30, 60, and 90 days at current pace
- Identify any acceleration or deceleration trends

### Day and Timing Strategy
- Which days of the week drive the most impressions?
- Which days drive the most engagement?
- Recommend an optimal posting schedule based on the data

### 5 Specific Content Recommendations
Based on everything above, give me 5 specific, actionable content recommendations. Each should include:
- The content angle or topic
- Why the data supports it
- Which audience segment it targets
- Expected impact based on patterns in my data

Keep analysis direct. Use numbers. No fluff.
