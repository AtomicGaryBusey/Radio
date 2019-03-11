# Radio

## Baofeng Radios

**Description**
CSV files with radio make/model in name are intended to be used with CHIRP. It's a pain in the ass to find an easy way to load frequencies onto Baofeng radios.

I totally understand why radio forums always play the SWIM (Someone Who Isn't Me) game, and try to play it extremely safe and vanilla from a legal perspective, but as someone who just wants the damn things to work I get frustrated by endless piles of "RTFM but once you're done don't do it and buy this Kenwood instead."

So here's some stuff you can use to just get Baofeng radios working. I live in the United States of America, so all files are relevant to the USA. Your mileage may vary outside the USA. Know what you're doing before you do it. Also, if you're going to go broadcasting on GMRS in the USA, go get a GMRS license from the FCC. It's cheap.

**Prerequisites**
1. Buy a Baofeng radio. The BF-888S and UV-5R are focused on because they're mainly what I've experience with.
2. Buy an official Baofeng USB programming cable. Do *NOT* go for a knockoff because it's 37 cents on eBay or Amazon. More info below.
3. Download and install CHIRP from the link below.
4. Configure the USB-COM drivers for the Baofeng.
5. Download one of the CSV files here that match your radio.

**Steps to Use the CSV Files in CHIRP** (Assuming a Windows PC.)
1. Connect the Baofeng radio to the USB programming cable, and the cable to your computer.
2. Open CHIRP and click **Radio** --> **Download From Radio**. Pick the correct **Port**, **Vendor** (Baofeng), and **Model**, then click OK.
3. Click **File** --> **Import**, and select the downloaded CSV. Click OK.
4. Click **Radio** --> **Upload To Radio**.
5. Disconnect radio. Test. ???? Profit.

**Additional Information**
* Details on the Baofeng USB cable situation: https://baofengtech.com/Programming-cable
* The latest version of CHIRP can be found here: https://trac.chirp.danplanet.com/chirp_daily/LATEST/
* FRS/GMRS frequency data can be found here: https://wiki.radioreference.com/index.php/FRS/GMRS_combined_channel_chart
* USA FCC GMRS License details: https://www.fcc.gov/general-mobile-radio-service-gmrs

**LEGAL DISCLAIMER:** These files are provided for informational purposes only and are not encouragement to violate laws and regulations as may apply to you in your operating area. I am not responsible for any choices you make or actions you commit which may run afoul of applicable laws and regulation. If you decide to use these frequencies on unapproved equipment in the United States and get a knock on your door from the FCC, it's entirely on you to solve. Fair warning. Lastly, I am not a lawyer, and I am not *your* lawyer. If you get in trouble, go hire a lawyer. Or not, I'm not your real dad, I can't tell you what to do.

**Personal FCC Notice:** I am putting these online in this way in good faith that nobody will be a dumbass with their radios and use them in a manner contrary to applicable laws and FCC regulations. I operate all radio equipment within the bounds of applicable laws and regulations in the United States of America. Contact me at **governmentinquiries (AT) zebeth (DOT) org** with any questions or concerns.
