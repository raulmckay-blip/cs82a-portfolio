# AI Prompt Log

I used Claude as a coding assistant on this project. This log lists what I asked, what it gave me, and how I checked it.

| Date | What I asked | What the AI gave me | How I checked it |
|---|---|---|---|
| 2026-10-22 | Help me start the code for my La Liga odds project: download all seasons from football-data.co.uk, clean them, and test if the odds are accurate. | The first version of the notebook: downloading the 26 season files, fixing the 2004/05 trailing-comma rows and the BOM in newer files, averaging odds across bookmakers, removing the bookmaker margin, calibration buckets with 95% CIs and z-tests, and the favorite/draw/underdog comparison. | *Ran the notebook top to bottom, verified every season had 20 teams and 380 matches (2000/01 and 2002/03 have 379 because one match each had no odds), and cross-checked a sample of matches by hand against the raw CSV files.* |
| 2026-10-22 | Simplify the notebook so it is easier to explain in a 3–5 minute walkthrough. | A shorter version: 10% buckets instead of 5%, three charts instead of four, and the favorite-strength table, home-wins chart, and betting-return section removed. | *Re-ran it and confirmed the key numbers (9,878 matches; favorites 51.4% vs 53.4%) matched the first version.* |
| 2026-10-24 | Move the AI-use note to the end, polish the wording so it reads like a report in my voice, and remove the emoji icons. | Cleaner wording for the markdown cells, a fix for a pandas warning, and three accuracy corrections to my takeaways (low-probability buckets sit slightly below the line, draws are not significant, and Limitation #3 softened). | *Compared each corrected sentence with the bucket and role tables in the notebook before accepting it.* |
