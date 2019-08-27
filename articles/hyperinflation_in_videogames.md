[Home](../index.md)

# Hyperinflation in videogames
![](https://img.shields.io/badge/Status-Work_in_progress-brown.svg) ![](https://img.shields.io/badge/Last_review-27/08/2019-green.svg)

What is hyperinflation? How does it appear in videogames? What are the best solutions to avoid it in your games? I'll try to answer all this questions.

## What is hyperinflation?
Well, according to Google, it's a "monetary inflation occurring at a very high rate" (duh). So a more accurate question should be: What is inflation? Here's a good definition provided by Investopedia:

    Inflation is a quantitative measure of the rate at which the average price level of a basket of selected goods and services in an economy increases over a period of time. It is the constant rise in the general level of prices where a unit of currency buys less than it did in prior periods.

This is a good example of how inflation appears in the real world due to many factors: producers can't make enough to meet demand (Demand-Pull inflation), goods shortage (Cost-Push inflation), etc.

![](images/inflation.png)

As you can see, inflation indicates a **decrease** in the **purchasing power**, in this case using United States Dollars (USD). Basically, keep this idea in mind: inflation indicates that your money is less valuable over time.

I'm not going into details but here are some good real examples of hyperinflation that lead to catastrophic results in their respective countries:

- Hungary (Pengö) 1945-1946. Worst case of hyperinflation in history. 1 USD = 4.6×10^29 Pengö (460.000.000.000.000.000.000.000.000.000) [Read](https://www.businessinsider.com/hungarys-hyperinflation-story-2014-4?international=true&r=US&IR=T)
- Germany (German mark) 1922-2923. 1 USD = 4,210,500,000,000 DM [Read](https://mashable.com/2016/07/27/german-hyperinflation/?europe=true)
- Venezuela (Venezuelan Bolívar) 2016-now. I've included this one since it's very notorious right now. Top exchange: 1 USD = 15843 VES. [Read](https://en.wikipedia.org/wiki/Hyperinflation_in_Venezuela)
- Other examples [here](https://www.fleur-de-coin.com/articles/worthless-money).


### And in videogames?

Videogames currencies work different than real ones, so the inflation appears due to different aspects. It can be seen mostly in **MMOs** (Massive Multiplayer Online) because the economy of this games is very important and have to last over time. It's not the case with real time strategy games, like League of Legends, because the money is only used in a single game and then disappears. If you are developing a videogame and you're planning to add an economy system, **be very careful matching your game genre**; in other words, don't use a in-game currency if you can avoid it and it's not necessary.

Inflation shows up on a videogame currency when players constantly gain in-game money directly from the system. That means that new money is "printed" every time a player kills a mob or completes a quest. In most of the games the players can buy/sell stuff with the in-game currency between each other and with NPCs (Non-Playable Characters)

![](images/pile_of_gold.gif)

If your game has a finite amount of money you have direct control over it so no hyperinflation should appear. But it's difficult to deal with a game with a specific currency sum. 


## How to deal with it?
Knowing that a hyperinflation is bad and could cause massive damage to your game. Let's see how to prevent it and deal with it.

- **NPCs**

One possible solution is to introduce NPCs in your game for the players with special deals or objects, that way all the money spent on the items bought to these NPCs is "destroyed".

- **Link to real world money**

Eve Online does this with PLEX. you can buy PLEX with real money and then exchange it with other players to gain ISK or use it to increase your subscription time.

Prices in 'The Forge' region.
01/01/2013 - sell 1.116.580 buy 1.096.000 start
24/08/2019 - sell 3.652.900 buy 3.514.030 last day
03/05/2019 - sell 4.476.700 buy 4.424.000 top
![](images/plex_price_history.png)

- **Control over the in-game currency creation**
- **Raise taxes**

You have to be careful with this one because too much high taxes can lead your players to stop playing the game.

- Abandon the old currency and switch to a barter economy
- Increase the production of goods and services ¿?
-

wow active players 1.7 million oct 2018 [[1]](https://gadgets.ndtv.com/games/news/world-of-warcraft-wow-subscription-numbers-battle-of-azeroth-1932930)

http://meminsf.silverstringmedia.com/labour/a-history-of-world-of-warcrafts-gold-economy/

https://www.adam4eve.eu/commodity.php?typeID=44992&regionID=10000002&avg=0&from=2013-01-01&until=2019-08-24#

* * *
## Leave a comment and get a cookie 🍪!

<div id="disqus_thread"></div>
<script>
    (function() {  // REQUIRED CONFIGURATION VARIABLE: EDIT THE SHORTNAME BELOW
        var d = document, s = d.createElement('script');
        
        s.src = 'https://guilleqp.disqus.com/embed.js'; 
        
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>