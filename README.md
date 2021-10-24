- 👋 Hi, I’m @rarodaro
- 👀 I’m interested in ...Programming mostly web apps , permutations, mathematics. web services CSHARP, .NET, ASP.NET
- 🌱 I’m currently learning ...Java app development ,CEH  certified ethical hacker
- 💞️ I’m looking to collaborate on ...security issues in website administrating access
- 📫 How to reach me ...via email dbrzovicmail@gmail.com

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

