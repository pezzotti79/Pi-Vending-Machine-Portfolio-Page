# Pi-Vending-Machine-Portfolio-Page #
![image](https://github.com/user-attachments/assets/fa39a714-e1de-4630-8010-34cf6643c5bd)
The Raspberry Pi features GPIO pins, which serve as dual-purpose inputs and outputs. These pins possess the capability to toggle between states, detect signals, and establish connections with external devices. Certain pins are permanently configured for power supply (5V or 3.3V) or ground. It is crucial to note that the pin numbers do not correspond to the GPIO numbers, necessitating the precise utilization of the correct GPIO number when programming.
# Vending Machine #
![image](https://github.com/user-attachments/assets/f1edac7d-8c47-44ee-8e55-cf80a05bdf3e)
A vending machine program on the Raspberry Pi maintains a record of coin credits. Pressing the COIN button increments the credit count by one, while pressing the VEND button decrements it by one if there are sufficient credits available. If no credits remain, pressing VEND does not have any effect. Upon each button press, the program updates the display to reflect the current number of credits.
# Vending Machine Code #
![image](https://github.com/user-attachments/assets/f31a426e-5461-478d-9093-80eaf0618402)
# Coin In Functionality #
![image](https://github.com/user-attachments/assets/3f56c52a-444a-4c22-869c-caabe15d63c0)
Upon inserting a coin and pressing the COIN button, the Raspberry Pi program increments the credit count by one. The updated credit count is then printed, and the coin is registered as available for vending. This ensures that each inserted coin is accurately tracked for future transactions.
# Vending Machine Functionality #
![image](https://github.com/user-attachments/assets/79ae9798-5f83-4c9a-a7c7-7ad3dab59040)
Upon pressing the VEND button, the program verifies the credit balance. If a credit is available, the VEND LED momentarily illuminates, the credit count is decremented by one, and the updated count is displayed. In the absence of credits, pressing the VEND button does not initiate any action. 
![image](https://github.com/user-attachments/assets/9c6d0656-8383-4812-8451-bc08556ff4fd)
# References #
Justice, M. (2021). “How Computers Really Work: A Hands-On Guide to the Inner Workings of the Machine.” No Starch Press, Inc.
