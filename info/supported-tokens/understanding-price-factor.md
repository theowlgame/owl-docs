# Understanding Price Factor

### Winning Multiple Matters, Not the Token Price.

When you enter any 3rd-party games, unless you are playing with our in-house games (Dice, Crash), the game will show you an estimate $ value of your wallet balance in your selected token.

_OWL Betting Case: Suppose you have 100 OWL token in your wallet, whose real-time price is $0.01 per OWL, you will see $1 as your gaming balance in any 3rd-party games such as slots, live casino and sports betting._&#x20;

When you bet in any 3rd-party game, you choose a $ value to bet, but in reality you are betting in your selected token. In the OWL Betting Case, when you choose to bet $0.1 in a slot game, you actually bet with $0.1/$0.01 = 10 OWL token.&#x20;

If you win 85 times of your bet, the game will show you get 85 \* $0.1 = $8.5 payout. You actually get $8.5/$0.01 = 850 OWL token. &#x20;

So in a nutshell, you bet 10 OWL token, won 85 times, and you get 850 OWL, no matter what the OWL token price is.  **The token price does NOT count, it only affects the '$' value balance you see in the games.  It also affects the $ amount of commission to pay to our 3rd party game providers. The bigger the $ value, the more the commission that we need to pay.**

$$
Payout = Winning Multiple * Token Amount
$$

### **​**​Price Factor

In order to adjust for the different price volatility of different tokens, OwlDAO applies a price factor for showing the wallet balances for a specific token in 3rd-party games.

For core tokens, such as BTC, ETH, USD stablecoins, BNB, whose price is more stable, we show the $ value by its real-time price. A.k.a Price Factor for core tokens equals to 1.

For community and frontier tokens, whose price is more volatile, they will be assigned to different price factors. While the maximum Price Factor is 1, the more stable the token price is, the bigger the Price Factor is.&#x20;

$$
In-Game Balance = Token Amount * Token Price * Price Factor
$$

By convention, community tokens that meet a certain amount of liquidity will have their Price Factor at 1, while Frontier tokens, which are easily rugged and have wild prices, will have their Price Factor at 0.001.



