# Ohio State Senate Election Simulations - Master Thesis 2025, Hertie Master of Public Policy

This repository contains the code, data structure, and analysis files used to simulate electoral outcomes in Ohio State Senate districts using various voting systems (e.g., Closed Primaries, TRW, IRV, Condorcet-Borda, Copeland, STV).

## Contents

- `Replication_File.Rmd`: Main R Markdown file with simulation logic and visualizations.
- `Ohio Senate Districts - 2012-2022 Election Results.xlsx`: Data file on all elections to the Ohio Senate from 2012 to 2022, sourced from the Office of the Ohio Sectretary of State.
- `dime_codebook_v2.pdf`: Codebook for using the [Database on Ideology, Money in Politics, and Elections](https://data.stanford.edu/dime) (DIME).

## Prerequisites

Before running the code, you will need to manually download the DIME external dataset containing candidate `CFscores`:

### 🔹 DIME Dataset

**Source**: Bonica, Adam. 2024. *Database on Ideology, Money in Politics, and Elections: Public version 4.0* [Computer file]. Stanford, CA: Stanford University Libraries.  
**Link**: https://data.stanford.edu/dime

1. Go to [https://data.stanford.edu/dime](https://data.stanford.edu/dime).
2. Under “Candidate/Recipient Files”, download the file:
   - `dime_recipients_1979_2024.rdata`
3. Place the file in your working directory


## Citations
1. Bonica, Adam. 2024. Database on Ideology, Money in Politics, and Elections: Public version 4.0 [Computer file]. Stanford, CA: Stanford University Libraries. https://data.stanford.edu/dime.

2. Office of the Secretary of State of Ohio. 2024. Ohio Election Results, 2012–2022 [Computer file]. Columbus, OH: Ohio Secretary of State. https://www.ohiosos.gov/elections/election-results/

## License
This project is licensed under the [MIT License](LICENSE).

MIT License

Copyright (c) 2025 Corbin Tyler Cerny

Permission is hereby granted, free of charge, to any person obtaining a copy
...
