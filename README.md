# VDP Retro board Rev 2.1


A composite video board for a [2063-Z80](https://github.com/johnwinans/2063-Z80) board.

* Manuals for the TMS9118 VDP chip family 
    - [TMS9918 1982](http://www.bitsavers.org/components/ti/TMS9900/TMS9918A_TMS9928A_TMS9929A_Video_Display_Processors_Data_Manual_Nov82.pdf)
    - [TMS9118 1984](https://map.grauw.nl/resources/video/ti-vdp-programmers-guide.pdf)
	- [TMS9118 datasheet](https://www.datasheetarchive.com/pdf/download.php?id=066bc6d93d0e48fb129b2e6e6f420933c63ad7&type=M&term=TMS9118) (Sorry, this is the only place I could find it.)

* A youtube playlist discussing this project and how to build your own can be found in 
[John's Basement](https://www.youtube.com/watch?v=oekucjDcNbA&list=PL3by7evD3F51Cf9QnsAEdgSQ4cz7HQZX5)
* A PDF version of the schematic can be found [here](2068-Z80-TMS9118.pdf).

![PC Board Image](2068-Z80-TMS9118.png "Composite video board for the 2063-Z80")

# Where to get parts

I ordered my VDP on Ebay from [hifiic](2068-Z80-TMS9118.sch) on [this auction](https://www.ebay.com/itm/322191622624?hash=item4b041e01e0:g:ldwAAOxyQBJREMaa)

I ordered my DRAMs on Ebay from [ruixin2020](https://www.ebay.com/str/ruixin2020) on [this auction](https://www.ebay.com/itm/164305877650)

I ordered my long pin header on Amazon [here](https://www.amazon.com/gp/product/B084Q4W1PW/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)

See the [BOM](2068-Z80-TMS9118.md) for the rest of the parts and Digikey order numbers.

# Release Notes
## Rev 2 

Change J6 and add J7 to allow routing the IRQ signal from the VDP to the IRQ, NMI, or A8_1

## Rev 2.1 

Add support for MSX joypad
