# PhotoCopyCircuit
This is the design for the deeds simulatoins of the photocopy machine. We have used 3 JK flip-flop for the 3-bit count-up program with a negative triggered clock. 3 XOR gate, 3 inverters and 1 NAND gate for the 3-bit comparator. There are 2 switches for Power and Wi-Fi. Also, there are 3 switches for password.
THE Xerox Machine was operational. After upgrading the code from 2-bit to 3 bits using Win CUPL and burning the code to PLD G22V10 by using Well On software, the IC worked on the Circuit board.
Use the switches to input the number of copies user wants to print, connect to the Wi-Fi, give the password and press Power. If any problem occurs the user can press the power again to stop the printing at that moment.
