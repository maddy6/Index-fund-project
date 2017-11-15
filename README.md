# Index-fund-project

Alkon30 Index Fund Summary: An Alkon30 index fund that will use the ICO funding to buy the underlying crypto assets from crypto universe. Their is no broker fees, no exit load, no minimum investment and full control over your underlying assets. Backed by full blockchain transparency.

Outline of the Project

Price Index Calculations: The Alkon30 is computed using the free-float market capitalisation weighted method wherein the level of the Index reflects the total market value of all the crypto’ s in the Index relative to the base period January 1, 2013.

The Alokon30 is a market index and follows for the derivation the Laspeyres Index. The index of Laspeyres is defined as Laspeyres Index

Liquidity Rule:

0.25 percentile of ADTV(Average Daily Trading Volume)
0.25 percentile of ADTC(Average Daily Traded Coins )
Weights: Each crypto’ s in CRIX is weighted with its market capitalization.

Reallocation: The reallocation period of the Alkon30 is 7 Days to ensure that the index is always up to date.

Action Items:

Build an Index fund with basic algorithm criteria.
(I have already started the work on construction of index fund based on Market Capitalization criteria) Following points, I’m considering during the construction of Index.

Liquidity of the respective coin
Inflation Adjusted Market Capitalization
Weights calculation (I can use Markowitz efficient frontier to calculate the weights)
Availability of coin & its exchange on Coinigy(as we are going to use Coinigy for integration with our platform)
Time Line for building the basic prototype will be within 20 days. (Expected date: 25-29th Nov)

Data Resources .... (Extract the necessary data)
I have researched the different platforms, where we can use existing set of platforms for integration with our platforms.

Coinigy:- I have found Coinigy is the best platform we can use and also its cost effective. (See the Ref for coinigy at the bottom of this post)

Also we need data from different exchanges as we are going to use weighted average method to calculate the price for underlying currencies.

e.g Lets consider to obtain the data for Bitcoin, we need to consider the data from exchanges where the volume of the bitcoin is more. Task: List of coins and fetch the data from respective exchanges

Also we need to capture the circulating supply of coins for underlying crypto’ s to calculate the Inflation adjusted market capitalization. We can use Blockchain explorers to verify the coin transaction history and statistics.

Data Storage Platform
Currently I'm building local platform for our prototype. In future, we can either go with AWS or Google Cloud Platform.

ICO Planning

Technical whitepaper Credible technical roadmap Plausible business roadmap clear token distribution model

Prototype

Token Distribution

Team

Legal Aspects

Website and newsletter Social Media Blog Community channel

Pre-ICO Listing & Support

ICO: Website Security & Stability

Post ICO: Token Release

Resources/References for Other Competitors

Bitwiseinvestment:- Privately Operating Index Fund Consist of 10 Cryptos.

https://www.bitwiseinvestments.com/

They have Index Committee to evaluate and take necessary action in unexpected situations.

The Index is evaluated and studied on an ongoing basis. The Index Committee regular meeting is held every quarter to fully evaluate the health of the index. In this meeting, variables such as the eligibility liquidity are benchmarked against new market conditions. Also new data sources are considered for inclusion, and old ones are considered for exclusion. Special meetings can be called when unexpected market conditions arise such as hard forks, extreme price movements, or serious issues in data availability.

Reference for Bitwiseinvestments https://blockonomi.com/crypto20/ https://www.bloomberg.com/news/articles/2017-10-02/digital-coin-index-fund-startup-wants-to-be-vanguard-for-crypto

Crypto20:
https://www.crypto20.com/en/

Reference for Crypto20 https://github.com/cryptotwenty https://static.crypto20.com/pdf/c20-whitepaper.pdf?_ga=2.138620275.1305152954.1510135804-1645777452.1510135804

Bit20 Index Fund
http://www.bittwenty.com/

Reference for Bit20 https://steemit.com/bitshares/@estefantt/bit20-the-cryptocurrency-index-fund

Swissborg SwissBorg aims be the first Swiss cyber bank offering tailor-made crypto investment services https://swissborg.com/en/
Reference for Swissborg https://swissborg.com/en/documents.html https://swissborg.com/files/swissborg-technical-whitepaper.pdf

Data Resources: Coinigy Platform: -

Coinigy is your all-in-one platform for digital currency

Trade on 45+ of the most popular exchanges
At present time they're crunching over 3.5 million trades per week across 2244 markets.
Live exchange rates
High-Frequency Trading
Smart Contracts
Coinigy API Available https://www.coinigy.com/api-documentation/

Pricing https://www.coinigy.com/pricing/

1 Month trial Free
$15/m when purchased annually
