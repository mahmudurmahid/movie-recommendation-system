# 🎬 Movie Recommendation System

A comprehensive movie recommendation system leveraging various filtering techniques to provide personalized movie suggestions.

---

## 📖 Table of Contents

- [🧑‍🍳 User Experience (UX)](#-user-experience-ux)
  - [🧾 User Stories](#-user-stories)
  - [🎨 Design](#-design)
    - [🗂 Interface Structure](#-interface-structure)
    - [🌈 Color Scheme & Typography](#-color-scheme--typography)
- [🚀 Features](#-features)
  - [✅ Implemented Features](#-implemented-features)
  - [🛠️ Planned Improvements](#-planned-improvements)
- [💻 Technologies Used](#-technologies-used)
  - [🧑‍💻 Languages Used](#-languages-used)
  - [📚 Libraries Used](#-libraries-used)
  - [📁 Project Files](#-project-files)
- [🛠 Installation & Usage](#-installation--usage)
  - [⚙️ How to Run](#️-how-to-run)
  - [🧾 Configuration](#-configuration)
  - [🔒 Security & Environment Configuration](#-security--environment-configuration)
    - [🧑‍💻 Use of python-dotenv](#-use-of-python-dotenv)
    - [🔧 Setting Up a Forked Repository](#-setting-up-a-forked-repository)
- [✅ Testing](#-testing)
  - [🧪 Test Scenarios Checklist](#-test-scenarios-checklist)
  - [🧪 Running Tests](#-running-tests)
- [🙌 Credits](#-credits)
  - [👨‍💻 Author](#-author)
  - [🧰 Tools & Technologies](#-tools--technologies)
  - [📚 Learning Resources & Documentation](#-learning-resources--documentation)

---

## 🧑‍🍳 User Experience (UX)

### 🧾 User Stories

- As a movie enthusiast, I want to receive movie recommendations based on my preferences.
- As a data analyst, I want to understand different recommendation techniques.
- As a developer, I want to explore the implementation of various filtering methods.

### 🎨 Design

#### 🗂 Interface Structure

The project is structured into separate Jupyter Notebooks, each demonstrating a different recommendation technique:

- `popularity_based_filtering.ipynb`
- `content_based_filtering.ipynb`
- `collaborative_based_filtering.ipynb`

#### 🌈 Color Scheme & Typography

As this project is notebook-based, standard Jupyter Notebook themes and fonts are used.

---

## 🚀 Features

### ✅ Implemented Features

- **Popularity-Based Filtering**: Recommends movies based on overall popularity metrics.
- **Content-Based Filtering**: Suggests movies similar to a user's liked movies by analyzing content features.
- **Collaborative-Based Filtering**: Recommends movies by finding similarities between users' preferences.

### 🛠️ Planned Improvements

- Integration of a web interface using Flask or Streamlit.
- Incorporation of hybrid recommendation systems combining multiple techniques.
- Enhancement of data visualization for better interpretability.

---

## 💻 Technologies Used

### 🧑‍💻 Languages Used

- Python 3.13

### 📚 Libraries Used

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `surprise` (for collaborative filtering)

### 📁 Project Files

- `popularity_based_filtering.ipynb`: Demonstrates popularity-based recommendation.
- `content_based_filtering.ipynb`: Implements content-based filtering.
- `collaborative_based_filtering.ipynb`: Showcases collaborative filtering techniques.
- `movies.csv`: Dataset containing movie information.
- `ratings.csv`: Dataset containing user ratings.
- `credits.csv`: Additional dataset with movie credits.
- `requirements.txt`: Lists all required Python libraries.

---

## 🛠 Installation & Usage

### ⚙️ How to Run

1. **Clone the repository**:

```bash
git clone https://github.com/mahmudurmahid/movie-recommendation-system.git
cd movie-recommendation-system

2. **Create a virtual environment (optional but recommended)**:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install the required libraries**:

```bash
pip install -r requirements.txt
```

4. **Run the Jupyter Notebook**:

```bash
jupyter notebook
```

Open the desired .ipynb file to explore the recommendation techniques.

### 🧾 Configuration

Ensure that the datasets (movies.csv, ratings.csv, credits.csv) are placed in the project directory. No additional configuration is required.

---

## 🔒 Security & Environment Configuration

### 🧑‍💻 Use of python-dotenv

Currently, the project does not utilize environment variables. For future enhancements, especially when integrating APIs or deploying the application, consider using python-dotenv to manage environment variables securely.

### 🔧 Setting Up a Forked Repository

1. Fork the repository on GitHub.

2. Clone your forked repository:

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

3. Set up the upstream remote:

```bash
git remote add upstream https://github.com/mahmudurmahid/movie-recommendation-system.git
```

4. Pull the latest changes from the original repository:

```bash
git pull upstream main
```

## ✅ Testing

### 🧪 Test Scenarios Checklist

- [x] All notebooks run without errors.
- [x] Each recommendation method outputs valid and expected results.
- [x] Datasets load successfully.
- [ ] Web interface integration (Streamlit/Flask/Django) to be tested once implemented.
- [ ] Automated unit tests using `pytest` or `unittest` (planned).

### 🧪 Running Tests

Currently, testing is manual via Jupyter Notebooks:

1. Open each notebook file:
   - `popularity_based_filtering.ipynb`
   - `content_based_filtering.ipynb`
   - `collaborative_based_filtering.ipynb`
2. Run all cells sequentially.
3. Check outputs for:
   - Proper data loading.
   - No runtime errors.
   - Accurate recommendation outputs.

Future improvements will include:
- Unit tests for recommendation functions.
- Web interface testing with `pytest` and `selenium`.

---

## 🙌 Credits

### 👨‍💻 Author

- **Mahmudur Mahid**  
  [GitHub Profile](https://github.com/mahmudurmahid)

---

## 🧰 Tools & Technologies

- Python
- Jupyter Notebook
- scikit-learn
- Surprise library
- MovieLens dataset

---

## 📚 Learning Resources & Documentation

- [MovieLens Dataset](https://grouplens.org/datasets/movielens/)
- [Surprise Library Documentation](http://surpriselib.com/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
