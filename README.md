
![ʻākohekohe](https://github.com/grassfedreeve/akohekohe/blob/main/img/akohekohe_photo.jpg?raw=true)

# ʻākohekohe
26-key, column-staggered, unibody-split keyboard made with [ergogen](https://github.com/ergogen/ergogen) and [KiCad](https://www.kicad.org/). Named after the [ʻākohekohe bird](https://www.mauiforestbirds.org/akohekohe/), (“AH-kohay-kohay”), consider donating to the Maui Forest Bird Recovery Project. 

Basically a ZilpZalp with thumbs cut off, and the most comfortable layout I have found. 

Two versions for choc switches are available:
- The default-spacing solder-only version (in the [pcb](https://github.com/grassfedreeve/akohekohe/tree/main/pcb) directory)
- The minimal-choc-spacing solder-only version with the tightest spacing that choc V1 switches allow for (in the [pcb_min_choc](https://github.com/grassfedreeve/akohekohe/tree/main/pcb_min_choc) directory)
  **Note:** You will have to procure min-spacing keycaps. I am not aware of any commercial solution. Recommendation: [Philadelphia Minimalist](https://github.com/pseudoku/PseudoMakeMeKeyCapProfiles/blob/master/Philadelphia_Minimalist.scad) by [Pseudoku](https://github.com/pseudoku). There are also currently no 1.5u min-space keycaps, these will need to be generated.

**Warning:** The min-choc-spacing version has not been tested yet!

# Keymap
Example keymap for how you might use this many keys, created using caksoylar's great [keymap-drawer](https://github.com/caksoylar/keymap-drawer)
![keymap](https://github.com/grassfedreeve/akohekohe/blob/main/img/example_keymap.svg)
Alternative base layouts, Colemak DH, [Bird](https://github.com/jcmkk3/bird-layout), and a Gallium mod shared to me by [ssbb](https://github.com/ssbb) are also great options:
![altbase](https://github.com/grassfedreeve/akohekohe/blob/main/img/alt_base.svg)

## BOM
- 1 pcb
- 1 Seeed XIAO compatible controller
- 26 sod123 diodes
- 26 kailh choc low profile switches
- 26 keycaps

wireless parts (optional)
- [45mAh 351020 battery](https://www.ebay.com.au/itm/175319348479)
- [5mm pogo pin](https://www.aliexpress.com/item/1005006095992803.html?spm=a2g0o.order_list.order_list_main.35.78fd1802qp0XdF)
- [jumper](https://www.aliexpress.com/item/32827199777.html?spm=a2g0o.order_list.order_list_main.30.78fd1802qp0XdF)
## Firmware
ZMK is what I use and have setup a module for: [ākohekohe ZMK Module](https://github.com/grassfedreeve/zmk-keyboards-akohekohe) 
That being said the matrix is the same as a Hummingbird so you can use hummingbird firmware just fine on whichever firmware you enjoy.

## Inspiration & Thanks
- jcmkk3's [rufous](https://github.com/jcmkk3/trochilidae#rufous) hummingbird variation. Of which I used the Ergogen config, routing, and footprints.
- apfel's [zilpzalp](https://github.com/kilipan/zilpzalp) keyboard
- PJE66's [hummingbird](https://github.com/PJE66/hummingbird) keyboard
- Weteor's [grumpy](https://github.com/weteor/Grumpy) and [fitis](https://github.com/weteor/fitis)
- apsu's [aptmak](https://github.com/apsu/aptmak) keyboard layout
