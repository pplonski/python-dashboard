# Dashboard in Python 🐍

This project was created in Python. The dashboard was built in Jupyter Notebook. The data is fetched online from:
- Yahoo Finance service,
- Binance REST API,
- Open Meteo REST API.

The website and dashboard are served with <a href="https://github.com/mljar/mercuruy" target="_blank">Mercury</a> framework. It turns Jupyter Notebook to web application. It adds interactive widgets to notbook based on the YAML header (from the first raw cell in the notebook). 

The code for this website: [github.com/pplonski/python-dashboard](https://github.com/pplonski/python-dashboard).

### Schedule ⏰

The dashboard is executed daily from Monday to Friday at 8.30 AM. The scheduled execution is controlled by `Mercury`. There is `schedule` parameter in the YAML with crontab string.

### Email notification 📨

The dashboard can send an email notification if conditions on monitored values are met. The email sending is written with `smtplib` library.


## Dashboards 📊
