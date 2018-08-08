## Bet365 Scraper

This is a Python script to grab data for betting odds from the site https://bet365.com/ using Selenium.

# Why Selenium?

I would have preferred to use something like BeautifulSoup, but Bet365 has always been my go-to site for sportsbetting, and as far as I can tell there isn't a way to link directly to a market. For example, there is nothing along the lines of https://bet365.com/basketball/nba/futures/mvp as a way to get to the market for the NBA's Most Valuable Player. So instead, using Selenium we navigate there in Firefox from the home page.
