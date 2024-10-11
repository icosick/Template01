# Template01

```
git checkout --orphan tmp
git commit -m "Initial Commit"
git checkout -B main
git branch -d tmp

pip install -r requirements.txt
streamlit run app.py
```