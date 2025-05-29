# Traffic-Lights-In-VHDL
Made this little project in Vivado using VHDL. Made it for the Nexys A7. 
## Here's how it works:
The "administrator" enters two 8-bit numbers using the switches available on the Nexys A7.
Then pushes the N17 button to "Program" the Traffic-Lights ( or waits for the count-downt to start. It's just a reset).
The left side represents the displayed information for pedestrians:

1: Seven segment count down that shows how much time the pedestrian has to wait 

2: RGB LED that :

    a. is Red when the pedestrians shouldn't pass
    b. is Green when they should

The right side represents the displayed information for cars:

1: Seven segment count down that shows how much time the driver has to wait

2: RGB LED that :

    a. Is red when the cars shouldn't cross
    b. Is yellow 10 seconds before red
    c. Is green when the cars should pass

## Here's a video of it working:


https://github.com/user-attachments/assets/53eaba6f-abe9-473b-bd82-124709079ce8

