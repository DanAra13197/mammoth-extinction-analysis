# Mammoth Extinction Analysis

## What I'm Trying to Figure Out
How much did the Arctic ecosystem really change when mammoths went extinct 10,000 years ago? And can we use modern rewilding experiments to predict what bringing them back would actually do?

## My Hypothesis
When mammoths and other megafauna disappeared, the productive "mammoth steppe" grasslands turned into the mossy tundra we see today. If I'm right, modern sites with reintroduced herbivores (like Pleistocene Park) should show ecosystem characteristics somewhere between ancient grasslands and current tundra.

## The Data I'm Using
- **Pleistocene Park data** (Windirsch et al. 2022 from PANGAEA) - soil temp, carbon, vegetation from areas with different herbivore densities
- **Ancient DNA and pollen records** - what the vegetation actually looked like over the last 50,000 years

## My Approach
Build regression models using modern rewilding data (herbivore density → ecosystem changes), then use those models to "predict backwards" to the Pleistocene. Check if my predictions match what the ancient DNA and pollen data actually show.

## Project Structure
- `data/raw/` - Original datasets (never modified)
- `data/processed/` - Cleaned data for analysis
- `notebooks/` - Jupyter notebooks with all the analysis
- `figures/` - All the plots and graphs

## Why This Matters
Colossal Biosciences is trying to bring back mammoths by 2028. Before spending millions, someone should figure out if it'll actually help the ecosystem or if we're just making expensive zoo animals.
