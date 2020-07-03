# MarketStore
The market store offers 3 different kinds of membership cards : bronze, silver and gold. Each card has a unique discount rate and can calculate the discount for a purchase.
In order to receive info about a card, each card uses the .ToString() method to output its content.

The output is 4 lines which consist of purchase value, discount rate, discount and total amount.

There are 6 files in this project:

 - The StartUp.cs file initializes the 3 types of cards and prints on the console their individual output.
 
 - The Card.cs is the base class for all card types. It gives them the functionality and blueprint they need in order to carry out their tasks.
 
 - The Owner.cs is the class containing information regarding the owner of a card. It contains information required in some companies in order to create a membership card.
 
 - The BronzeCard.cs, SilverCard.cs and GoldCard.cs are the 3 types of cards which inherite the Card.cs base class. 
   The only part they change is the virtual method GetDiscountRate(). Each card has a different formula or logic that processes the discount rate. That is why it is overriding the method.
