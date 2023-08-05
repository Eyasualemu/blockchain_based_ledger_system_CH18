# blockchain_based_ledger_system_CH18

BlockChain
# Technology 

These are the technologies the user can use to run the solution 
•	IDE -- VSCode  
•	Programing Language -- Python 
•	Repository -- Github --To download the solution file. It's saved in github as public
•	Streamlit – For the web app

 # Contributors 
 The solution is developed by Eyasu Alemu LinkdIn account -- https://www.linkedin.com/in/eyasu-a-684854112 Email -- Bekaqa01@gmail.com Phone Number -- 202 344 0733

Using blockchain technology, blockchain-based ledger system, complete with a user-friendly web interface

The following steps performed 

1.	Create a Record Data Class
2.	Modify the Existing Block Data Class to Store Record Data
3.	Add Relevant User Inputs to the Streamlit Interface
4.	Test the PyChain Ledger by Storing Records



1. Create a Record Data Class

•	Define a new class named Record.
•	Add the @dataclass decorator immediately before the Record class definition.
•	Add an attribute named sender of type str.
•	Add an attribute named receiver of type str.
•	Add an attribute named amount of type float.

2. Modify the Existing Block Data Class to Store Record Data

Rename the data attribute to record and set the data type of the record attribute to Record

3.	Add Relevant User Inputs to the Streamlit Interface

•	Delete the input_data variable from the Streamlit interface.
•	Add an input area where you can get a value for sender from the user.
•	Add an input area where you can get a value for receiver from the user.
•	Add an input area where you can get a value for amount from the user.
•	As part of the Add Block button functionality, update new_block so that Block consists of an attribute named record, which is set equal to a Record that contains the sender, receiver, and amount values. The updated Blockshould also include the attributes for creator_id and prev_hash.

4.	Test the PyChain Ledger by Storing Records

•	Navigate and run the code from terminal 
![image](https://github.com/Eyasualemu/blockchain_based_ledger_system_CH18/assets/44585226/7b073ba6-7e60-489c-91e5-113c279fb241)

•	Enter Sender, receiver, and amount input 
![image](https://github.com/Eyasualemu/blockchain_based_ledger_system_CH18/assets/44585226/18201eb6-0367-4679-8a73-c0d198973d18)

•	block contents and hashes in the Streamlit drop-down menu. 
![image](https://github.com/Eyasualemu/blockchain_based_ledger_system_CH18/assets/44585226/f50e064d-d393-4a8e-9b9f-a397d957e392)


https://github.com/Eyasualemu/blockchain_based_ledger_system_CH18/assets/44585226/74482d8f-fa4f-4fbc-a5ce-623972661283






