# AI-Based Travel Planning and Personalized Trip Recommendation System

A Python travel planner that recommends tourist attractions and creates a day-wise itinerary based on a user's destination, trip duration, budget, and interests.

## Features
- Choose from Chennai, Goa, Ooty, Bangalore, and Kerala.
- Select a travel interest such as Nature, Beach, History, Culture, or Entertainment.
- Recommend places using category matching and attraction ratings.
- Generate a day-wise itinerary.
- Estimate transportation, accommodation, food, and attraction costs.
- Check whether the estimated trip cost fits the user's budget.
- Use an interactive Gradio interface.

## Technologies Used
- Python
- Pandas
- Gradio

## Project Files
- `travel_planner.py` — main application.
- `requirements.txt` — required Python packages.
- `travel_dataset.csv` — sample tourist attraction dataset used by the project.
- `.gitignore` — files Git should ignore.
- `LICENSE` — MIT license.

## Run Locally
1. Install Python 3.10 or newer.
2. Open a terminal in this project folder.
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the application:

   ```bash
   python travel_planner.py
   ```

5. Open the local Gradio URL printed in the terminal.

## How It Works
The application filters attractions by destination and preferred category, sorts matching places by rating, and prepares activities for each day. It estimates trip costs using predefined transportation, accommodation, food, and attraction costs, then compares the total with the user's budget.

## Important Notes
- Recommendations come from a predefined sample dataset; they are not live search results.
- Cost estimates are illustrative and may not reflect current prices.
- The current implementation uses rule-based filtering and rating sorting; it does not train a machine-learning model.
- This project is intended for learning and demonstration purposes.
