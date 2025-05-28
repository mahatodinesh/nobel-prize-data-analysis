# Nobel Prize Data Analysis

This project explores the history and trends of the Nobel Prize winners from 1901 to 2023 using a dataset provided by the Nobel Foundation API. The aim is to answer meaningful questions about gender, nationality, categories, and repeat winners using data analysis and visualization techniques.

## 🏆 About the Nobel Prize

The Nobel Prize is one of the most prestigious international awards, first awarded in 1901. It honors individuals and organizations that have made outstanding contributions in the fields of:

- Physics
- Chemistry
- Physiology or Medicine
- Literature
- Peace
- Economic Sciences

Each winner receives a gold medal featuring Alfred Nobel, a cash prize, and international recognition.

## 📁 Dataset

The dataset is stored in the `data/` folder and contains:

- `nobel.csv` — Dataset with Nobel laureates from 1901 to 2023.

### Columns of Interest

- `year`: Year the prize was awarded  
- `category`: Nobel Prize category  
- `full_name`: Name of laureate  
- `sex`: Gender of laureate  
- `birth_country`: Country of birth  
- `birth_date`: Date of birth  
- `organization_name`: Affiliated institution  
- `organization_country`: Country of the institution  

## 🧪 Project Goals

The project answers the following questions:

- What is the most commonly awarded gender and birth country?
- How has the proportion of U.S.-born winners changed by decade?
- Which decade had the highest proportion of female winners by category?
- Who was the first woman to win a Nobel Prize and in what category?
- Who are the repeat winners (laureates who won more than once)?

## 📈 Visualizations

Two line plots are generated using Seaborn:

1. 📉 **Proportion of USA-born Nobel winners per decade**
2. 📈 **Proportion of female laureates by decade and category**

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nobel-prize-data-analysis.git
   cd nobel-prize-data-analysis
