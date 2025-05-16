# Proyek-Analisisi-Data-Submission

# How to set up
```
install python 3.12
install anaconda
```
## Setup Environment - Anaconda
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter
```
## Setup Environment - Shell/Terminal with anaconda prompt
```
mkdir submission
cd submission
jupyter-notebook .
```

## Run steamlit app
```
conda activate main-ds
pip install streamlit babel

```

## Run steamlit app
```
cd dashboard
streamlit run dashboard.py
streamlit run dashboard.py --server.headless true
```

## Deploy
https://wahyuozorahmanurungsubmission1.streamlit.app/
