- 👋 Hi, I’m @rarodaro
- 👀 I’m interested in ...Programming mostly web apps , permutations, mathematics. web services CSHARP, .NET, ASP.NET, solidity, blockchain ,dApps,onchain escrow systems
- 🌱 I’m currently learning ...Java app development ,CEH  certified ethical hacker
- 💞️ I’m looking to collaborate on ...security issues in website administrating access, Im into leverage trading compounding effect , lets say you know how to make 10 percent a day, u backtested it, multiply it with 365 or 250 if u trade forex , you have enourmous gains  during the year, right now i want to Apply my ethereum or more exact eth layer 2 polygon coin to the chain , and i could use some collaborators as well, untill now i have suceeded to build sucessfuly the blockchain functional token, with embedded funtions like antiwhale, soon i will escrow it, and before u san say cookie we be having a new banking system ready to provide fair transactions, holders rewards all without rugpulls, and suspicious trading activity . The token is fully charity because we want to help Gaza victims and Ukraine victims to get basic supply of medicines and food! join us ,support us , and here we can provide some threads on x and social networks:
- https://www.x.com/@BigcoinWorld
- or contact directly via mail :
- 📫 How to reach me ...via email dario.brzovic@gmail.com

<!---
rarodaro/rarodaro is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!--WAY I IMAGINATE FINISHING THE PROBLEMATICS OF CREATING THIS RELATIVELY SIMPLE APP IS NEXT: WARNING (THIS IS JUST A SIMPLE TEST APPLICATION NOT INTENTED FOR DEPLOYMENT APP)
FRONT END
java server page 

requesting the matches populating the dataSet for the table with games and matches and types you can bet with checkBox elements for types to choose (1 | 2 | x | x2 | x1 i 12)
input validation is obligatory for preventing the rogue type or invalid input requests.

BACK END OF THE APLICATION
Database MSSQL populated with test data matches and games.
No user Validation is implemented inthis app.

web service is managing methods after input data-data validation returning the wallet ammount and validating all the tickets properties

FOR NORMAL OFFER
WalletCheck(getWalletAmmount(),GetTicketSummAmmount());//SENDS FORWARD TO TICKET PROCESSING IF AMMOUNT IS VALID!IF NOT SENDS TO WALLET DEPOSIT PAGE!

ticketValidationNotMixedWithSpecialOffersIsValid(SelectedgamesAndTypesArray(),GetTicketID());//PULLS GAMES LIST WITH SELECTED RESULT PREDICTIONS AND CHECKS IF GAMES ARE NOT MIXED WITH SPECIAL OFFER GAMES RETURNS BOOLEAN

ticketValidationAndWalletSubtraction(WalletCheck(), GetTicketID)://THIS METHOD SHOULD CALCULATE THE SUMM OF ALL GAME MULTIPLIERS TO CALCULATE THE WINNING AMMOUNT MINUS THE MANIPULATION COSTS OF 0.05 MULTIPLIER(5%)
FOR SPECIAL OFFER

CheckMionimumOfFive(SelectedGamesAndTypesArray(), GetTicketID);//CHECKING THAT MINIMUM GAMES PLAYED IS NOT LESS THAN FIVE RETURNS BOOL!

WalletCheck(getWalletAmmount(),GetTicketSummAmmount());//SENDS FORWARD TO TICKET PROCESSING IF AMMOUNT IS VALID!IF NOT SENDS TO WALLET DEPOSIT PAGE!

ticketValidationNotMixedWithNormalOffersIsValid(SelectedgamesAndTypesArray());//PULLS GAMES LIST WITH SELECTED RESULT PREDICTIONS AND CHECKS IF GAMES ARE NOT MIXED WITH NORMAL OFFER GAMES RETURNS BOOLEAN

ticketValidationAndWalletSubtractionAndTicketFinnalProcessing()://THIS METHOD SHOULD CALCULATE THE SUMM OF ALL GAME MULTIPLIERS TO CALCULATE THE WINNING AMMOUNT MINUS THE MANIPULATION COSTS OF 0.05 MULTIPLIER(5%)

