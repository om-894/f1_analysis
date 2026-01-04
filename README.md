# f1_analysis

- (slide 1) How consistently do people overperform in qulifying vs race. What races have the biggest overperformances? And biggest underperformers in f1 based on qualifying to race
- (slide 2) Top 15 overperformers and underperformers in f1
- (slide 3)lead into heatmap of all of sennas seasons and percentages of his DNFs in a bar chart also include salo heatmap
- (slide 4) Who OWNED a circuit. best drivers at certain circuits e.g senna at monaco or hamilton at silverstone BUT WHO ELSE has gone unoticed. maybe use average finishing position
- (slide 4)Could any drivers who never scored points in their careers have scored points if the modern scoring system had been in place?
- (slide 5) Era dominance. How dominant was this driver relative to the races available in their era (regulations years- you can find lists of these)? wins_per_race = wins / races_started. obviously MS raced alot less than LH and even further back LF raced eeeeeeven less.
- (slide 6) how does constructer performance affect driver results. are there anomolies e.g raikonnen in 2012. whats the biggest percentage differenc based on constuctor teammates
- (slide 7) Fastest lap times for longest serving races like silverstone etc. (find this out by counting number of times a GP appears based on year in the dataframe). scattergraph would be nice here showing when the circuits changed over the years. Potentially pick circuits which have been there since the start e.g. Monaco, silverstone and visualising when the circuit changes came in. potentially also acknowledge the years that the circuit wasnt on the calendar


- 2024 season heatmap (unless i can scrape 2025 data)

Challenges 
- normalise points depending on era. make it the modern equivalent and sorting out grid positiona gained and lost in a race whilst including DNFs and Retirements.
- Stacking the bar chart (having to use index and convert to wide format etc.)
- splitting the f1 years into eras. theres not technically any defined years for the eras but i tried
- The lap times from qualifying. Had to replace missing values \N with NaN, then sensure each driver had three quali times.
