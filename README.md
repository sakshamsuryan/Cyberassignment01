## What It Does
* Scans URLs using a pre-trained Machine Learning model (`url_model.pkl`).
* Extracts URL structure and domain features (`features.py`).
* Runs live WHOIS and webpage checks (`live_checks.py`).
* Saves scan history in a local SQLite database (`db.py`).

## Tech Stack Used
* **UI:** Streamlit
* **ML & Data:** Scikit-Learn, Joblib, NumPy, Pandas
* **Network & Domain Checks:** Requests, BeautifulSoup4, python-whois, tldextract
* **Database:** SQLite3
* **Hosting:** Render

## How to Run Locally

```bash
git clone [https://github.com/shubhamkrmu/Phishguard.git](https://github.com/shubhamkrmu/Phishguard.git)
cd Phishguard
pip install -r requirements.txt
streamlit run app.py
