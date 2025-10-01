# 📊 Cohort Analysis on Online Retail Customers

This project is all about understanding **customer retention** using
cohort analysis.\
I worked with the **UCI Online Retail Dataset** and explored how
customers behave over time after their very first purchase.

------------------------------------------------------------------------

## 🌟 What this project does

-   Loads the **Online Retail dataset** directly from the UCI Machine
    Learning Repository.\
-   Cleans up the data (removing missing customer IDs, fixing dates).\
-   Groups customers into **cohorts** based on when they first
    purchased.\
-   Tracks those cohorts month by month to see how many people kept
    coming back.\
-   Visualizes everything with **heatmaps** (counts and percentages).

------------------------------------------------------------------------

## 🛠 Tools I used

-   **Python** (Pandas, Numpy) for data wrangling\
-   **Seaborn & Matplotlib** for plots\
-   **ucimlrepo** to fetch the dataset from UCI

------------------------------------------------------------------------

## 🔑 Key steps in the analysis

1.  **Create InvoiceMonth and CohortMonth** → figure out when each
    customer made their first order.\
2.  **Work out Cohort Index** → number of months since that first
    order.\
3.  **Build a retention table** → how many customers from each cohort
    came back in later months.\
4.  **Visualize it** → heatmaps that show the retention story clearly.

------------------------------------------------------------------------

## 📊 What the results show

-   Retention naturally drops off over time.\
-   Some cohorts stick around longer than others.\
-   You can spot when churn happens faster and use this to guide
    decisions on marketing or product strategy.

------------------------------------------------------------------------

## ▶️ How to run it yourself

Clone this repo and install the requirements:

``` bash
git clone https://github.com/your-username/cohort-analysis.git
cd cohort-analysis
pip install -r requirements.txt
```

Run the analysis:

``` bash
python cohort_analysis.py
```

Or open the notebook in Jupyter/Colab if you prefer exploring
interactively.

------------------------------------------------------------------------

## 🚀 Next ideas

-   Add revenue-based cohorts (not just customer counts).\
-   Compare seasonal effects on retention.\
-   Bring in other datasets like HR or SaaS subscriptions for broader
    applications.

------------------------------------------------------------------------

## 📜 License

This project is under the MIT License. Feel free to use and adapt!
