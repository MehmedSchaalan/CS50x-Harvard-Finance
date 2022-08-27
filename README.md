## CS50X-finance

### Brief description
You’re about to implement C$50 Finance, a web app via which you can manage portfolios of stocks. 
Not only will this tool allow you to check real stocks’ actual prices and portfolios’ values,
it will also let you buy (okay, “buy”) and sell (okay, “sell”) stocks by querying IEX for stocks’ prices.  

### Note
In the most recent commits, I change the database to Postgres to deloy to Heroku (the original project use sqlite).  
So if you clone the repo and it does not work in the local, rollback to ealier commit. 
You also need a key to access the stock API from IEX even though I public my key in this respo if you don't want to register to IEX.

### Workflow

    python -m venv env
    python env/scripts/activate.ps1
    python -m pip install requirements.txt
    flask run
