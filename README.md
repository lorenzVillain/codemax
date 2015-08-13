# codemaxecho "# codemax" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/lorenzVillain/codemax.git
git push -u origin master



//Create a function (stock_picker) that given a list of stock prices (from date 1 to date “n”) would return the buying date and the selling date with the max profit.
prices = [100, 90, 120, 80, 110, 140, 60, 110]
//position of the array indicates the date of the price
prices[0] = 100 # this is the price of the stock at day 0
stock_picker(prices) #=> [3, 5]
//max_profit is 60 #=> buying day 3 (80) and selling day 5 (140)
//Remember that you cannot sell on previous days


