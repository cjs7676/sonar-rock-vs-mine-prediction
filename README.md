//for opening the jupter file
in cmd jupyter notebook

// for environment
python -m venv venv

//for running the on web page
cd venv
cd Scripts
.\activate.ps1
streamlit run sonar_app.py  
ctrl+c
deactivate


//need of packages
pip install scikit-learn
pip install pyarrow
pip install numpy
pip install pandas
pip install streamlit pandas numpy

// for environment
python -m venv venv
