# CS3SY26_ProjectProposal

## Project Proposal Template

### Project Title or Name of the Application	: Beyblade X Builder
### Section			   	      : 9-Beryllium
### Group Members			    : CAISIP, CASCO, RAGAZA
### Date (Proposal Date)  : November 12, 2026

### Project Description:

- Our project will be a Beyblade X identifier and builder which will allow users to identify how powerful their beyblade is and if they are getting it for a fair price.  This aims to help beybladers around the country to find better deals for beyblades and know which ones are the strongest.

- The project will include the three types of Beyblade X beys, these being BX, UX, and CX. These all inherit from the Beyblade X abstract class (which itself inherits from the Beyblade class for further use). Each bey (an instance of BX, UX, or CX) has a blade, ratchet, and bit, and a price.

- Our target demographic is people who are interested in beyblades, both beginners and veterans who would like to get great deals.

![Sample Diagram](https://i.ibb.co/dsPCm0nK/yaaaayyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy.png)

### Goals:
The long-term goal of this project is to provide bladers with a Beyblade X identifier and builder that displays the competitive strength and price fairness of custom builds. This helps buyers nationwide to identify the strongest combinations and find the best deals.
 
- Make an abstract inheritance hierarchy in Python where BeybladeX (ABC) inherits from Beyblade (ABC), and subclasses (BeybladeX(BX), BeybladeX(UX), and BeybladeX(CX)) inherit from BeybladeX. 
- Apply object composition by combining Blade, Ratchet, and Bit objects (along with CX-specific blade2 and locking_chip attributes) into complete Beyblade instances using __init__ constructors. 
- Store and display part attributes, including spin direction, tier, types, stamina, speed, and pricing, through a standardized show_info() method across all classes. 
- Evaluate overall build strength and price fairness by generating rankings and comparing total performance vs. market price.
