# DIY-MOZA-GS-V2-USB-MOD
#### General Information
- This page is to collect information on how to mod a MOZA GS V2 wheel (now called GS GT by MOZA)


- This mod allows the Moza GS V2 and V2P (V2P not confirmed, still need to confirm) to be used on any wheelbase from any brand, as long as the actual physical QC connection is adapted of course.


-  A bit of backstory how this started:

    For me the GS Wheel is a perfect wheel in the 400-500€ price range, but it is limited by Moza to only work with their wheelbase and I wanted to explore other wheelbases from other brands, keeping my GS wheel tho. 
    So I started doing some research, trying to find out if its possible and if anyone had tried modding a GS wheel. Sadly I didn't find anything. 

    In the end I decided to blindly give it a try. With the switch to the V2 system on the wheelbases I had the assumption that the FSR and KS wheel use the exact same connection to the bases as the GS V2. Given that the FSR and KS wheels have universal      hub support, my conclusion was the the GS wheel should also get picked up by the hub and it did! 
    All that is needed is to take the 4 wires that go to the QC pcb at the end of the wheel and connect them to one of the hub ports and the hub recognizes the GS V2 wheel like any other officially supported wheel from Moza. 


- As a starting point, I have written some general instructions in a PDF format that can be found on this page, more information will follow as things progress.



#### Current issues & things to improve:

  - USB Power stability (only a problem when using the hub in the wheel)
  
    The hub uses USB 2.0, meaning 2.5W max for power, so 0.5A at 5V.

    When the hub gets less than around 1.5W of power it shuts down. Depending on the USB cable length used and the port its plugged into, the hub can end up getting under 1.5W.

    That's why Moza added the auxiliry USB port (the USB-C port) this stabilizes the power and the problem is resolved.

    With the hub being in the wheel, the goal is to only run one 4-wire cable to the wheel. This means one cable for each port is not possible. For now I get around this issue by plugging into a powered hub and using a relativly short not coiled cable,       but I want to find a more suitible solution in the future.

### Some pictures of the two type of setups I have tried (1 with the hub external and 1 with the hub inside the wheel):
  

- #### USB Mod with stock external hub (identical to the way the FSR or KS wheel from Moza work on the hub) 


![WhatsApp Image 2024-09-17 at 14 22 35](https://github.com/user-attachments/assets/ab2ff165-d699-41f1-bbc4-183ce77eb178)

![WhatsApp Image 2024-09-17 at 14 22 36](https://github.com/user-attachments/assets/50fc837b-aa24-42fa-8cb8-92613d1fa28a)


- #### USB Mod with internal Hub (true USB connection out of the wheel, the same way 3rd party wheels would be set up)

![WhatsApp Image 2024-09-23 at 14 06 51](https://github.com/user-attachments/assets/f5084fef-00ad-4b7a-9f1b-92cd552d7478)

![WhatsApp Image 2024-09-23 at 14 06 52](https://github.com/user-attachments/assets/1fb7592f-e87e-4ca0-8885-2ee29b437dfd)
