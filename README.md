# CV-passion-selector

## Intelligent Career Guidance Based on Your CV
The **CV Passion Selector** is a GenAI-powered tool designed to analyze your CV and suggest potential career or passion domains based on semantic understanding. Using state-of-the-art embedding models and retrieval techniques, this project offers a glimpse into how AI can assist individuals in discovering optimal career paths aligned with their experience and interests.

This project was developed as part of a **Capstone Initiative** focused on practical applications of Generative AI (Gemini) and Embedding Technologies.

## Features
- **Semantic CV Analysis** — Understands the context and skills from free-form CV text.
- **Passion Domain Matching** — Maps CV content to relevant career or passion areas.
- **Powered by GenAI Embeddings** — Utilizes advanced embedding models for deep text understanding.
- **Interactive Exploration** — Implemented in Jupyter Notebook for easy experimentation and visualization.

## Installation & Setup
1. Clone the Repository
```bash
git clone https://github.com/your-username/cv-passion-selector.git
cd cv-passion-selector
```

2. Create and Activate Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

3. Install Dependencies
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook
```bash
jupyter notebook
```

5. Navigate to notebooks/CV_Passion_Selector_Capstone.ipynb and run the cells.

## Usage
1. Open the notebook.
2. Find a cell with
```bash
example1_input = {...}
```
3. In the cell you can write your own example input.
4. Once you changed the example input, please, make sure to rerun all below cells after the example_input1 cell.
5. Hooray! The model chose for you the best fit opportunity.

## Improvements
While this notebook demonstrates core functionality and is as a prototype, there are exciting plans to evolve this project into a fully functional application:
### Planned Enhancements:
- Web Application Interface
Develop a user-friendly app where individuals can upload their CV (PDF/Docx/Text) and instantly receive career recommendations.

- Dynamic Passion Domain Database
Expand and update the database of career domains using live data from job markets and industry trends.

- Personalized Recommendations
Incorporate user preferences, goals, and soft skills for more tailored suggestions.

- Deployment
Host the app using frameworks like Streamlit, or FastAPI, possibly integrating cloud-based GenAI APIs.

- User Feedback Loop
Allow users to rate suggestions, improving the system via reinforcement learning.

## Acknowledgments
- Inspired by advancements in Generative AI and semantic search.
- Part of the **5-Day GenAI Intensive Course**.
