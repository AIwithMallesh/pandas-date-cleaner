# pandas-date-cleaner

A practical Jupyter notebook project for cleaning messy date formats in Pandas DataFrames. Ever dealt with dates in DD/MM/YYYY, ISO, month names, and garbage all mixed together? This guide turns that chaos into a clean, sorted timeline—perfect for data wranglers, analysts, or anyone tired of `ValueError: Unable to parse string`.

## 🚀 What's Inside?
- **Sample Dataset**: Fake event data with wild date formats (20 rows of fun).
- **EDA**: Spot the issues with naive parsing and failure rates.
- **Cleaning Magic**: Use `pd.to_datetime(format='mixed', dayfirst=True)` to handle the mess.
- **Validation**: Drop NaTs, sort by date, and check the range.
- **Visualization**: Matplotlib timeline plot to see your events flow.
- **Export**: Clean CSV ready for your next pipeline.

Runs in under a minute with just Pandas and Matplotlib. No fancy installs needed!

## 📋 Quick Start
1. Clone the repo:
2. git clone https://github.com/AIwithMallesh/pandas-date-cleaner.git
cd pandas-date-cleaner
2. Open `pandas_date_cleaner.ipynb` in Jupyter Notebook or Google Colab.
3. Run all cells—watch the dates get tamed!
4. Check `clean_events.csv` for your polished data and `event_timeline.png` for the viz.

## 💡 Why This Matters
Dates are sneaky— one bad format can break your entire analysis. This notebook is battle-tested for real-world ETL jobs, web scrapes, or CSV merges. Extend it: Add timezone handling or integrate with Airflow.

## 🛠️ Tech Stack
- Python 3.x
- Pandas (for data magic)
- Matplotlib (for plots)
- NumPy (for data gen)

Tested on Pandas 2.3.0+.

## 🤝 Contributing
Got ideas? Open a PR! Issues welcome for more date horrors.

## 📄 License
MIT—use it, tweak it, share it.

---

*Built with ❤️ by Mallesh. Inspired by endless date-parsing debugging sessions. Last updated: October 2025.*
