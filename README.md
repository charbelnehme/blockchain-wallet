# Unit 19 Homework: Cryptocurrency Wallet

![An image shows a wallet with bitcoin.](Images/19-4-challenge-image.png)

You work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

# Language and Tools 
* Python 
* Hashlib 
* Web3 
* Ganache 

# Instructions

* Import Ethereum Transaction Functions into the Fintech Finder Application
* Sign and Execute a Payment Transaction
* Inspect the Transaction on Ganache

## Step 1: Import Ethereum Transaction Functions into the Fintech Finder Application



```ruby
candidate_database = {
    "Charbel": ["Charbel", "0x517131C89a9960Ee3508D01C41e88DCeC083318f", "4.1", .16, "Images/charbel.jpg"],
    "Lane": ["Lane", "0x0f20a2B2E59C324164cd22D5E723bA08a429D6f9", "4.3", .20, "Images/lane.jpeg"],
    "Ash": ["Ash", "0xA2d16fD54a28e54272632491F7ff6D972966d9D2", "5.0", .33, "Images/ash.jpeg"],
    "Jo": ["Jo", "0x7c86061E24668fc2f2a66321AE60359253Ba8130", "4.7", .19, "Images/jo.jpeg"],
}

# A list of the FinTech Finder candidates first names
people = ["Charbel","Lane", "Ash", "Jo"]

def get_people():
    """Display the database of Fintech Finders candidate information."""
    db_list = list(candidate_database.values())

    for number in range(len(people)):
        st.image(db_list[number][4], width=200)
        st.write("Name: ", db_list[number][0])
        st.write("Ethereum Account Address: ", db_list[number][1])
        st.write("FinTech Finder Rating: ", db_list[number][2])
        st.write("Hourly Rate per Ether: ", db_list[number][3], "eth")
        st.text(" \n")
``` 

## Step 2: Sign and Execute a Payment Transaction



## Step 3: Inspect the Transaction


