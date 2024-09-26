```mermaid
flowchart LR
P(Product) ---> |Models and sale event| S(Sale)
C(Customer)---> |Buy the Shoe from the Sale| S(Sale)

S -->|Is| B(Bought) & N(Not Bought)
B -...-> |Less in Stock| I 
N -...-> |Have a good day!| L(Later)

P ---> |Do you have the new Nike Air Jordan?| I(Inventory)

I -->|How many shoes| St(Stock)
St -..-> |16 Nike Jordans| P

C <--> |Wanted Shoe| P

```

### This shoes how the Nike store functions with getting and providing shoes to customers. 
#### Products is responsible for providing models for the shoe and gives a sale.
#### Customers get attrated to the sales of the Shoe and the model
#### Customers would either Buy or dont buy the shoe from the deal
#### If they do buy the shoe, then the stock of the shoe dcreases
#### If there is no deal, then the customer leaves the store
#####
