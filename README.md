
![ʻākohekohe](https://github.com/grassfedreeve/akohekohe/blob/main/img/akohekohe_photo.jpg?raw=true)

# ʻākohekohe
26-key, column-staggered, unibody-split keyboard made with [ergogen](https://github.com/ergogen/ergogen) and [KiCad](https://www.kicad.org/). Named after the [ʻākohekohe bird](https://www.mauiforestbirds.org/akohekohe/), (“AH-kohay-kohay”), consider donating to the Maui Forest Bird Recovery Project. 

Basically a ZilpZalp with thumbs cut off, and the most comfortable layout I have found. 

# Keymap
Example keymap for how you might use this many keys:
![keymap](https://raw.githubusercontent.com/grassfedreeve/akohekohe/main/img/example_keymap.svg?token=GHSAT0AAAAAACTVYPRXH7SLK7HHQCHEVM7YZU263RQ)

## BOM
- 1 pcb
- 1 Seeed XIAO compatible controller
- 26 sot23 diodes
- 26 kailh choc low profile switches
- 26 keycaps

wireless parts (optional)
- [45mAh 351020 battery](https://www.ebay.com.au/itm/175319348479)
- [5mm pogo pin](https://www.aliexpress.com/item/1005006095992803.html?spm=a2g0o.order_list.order_list_main.35.78fd1802qp0XdF)
- [jumper](https://www.aliexpress.com/item/32827199777.html?spm=a2g0o.order_list.order_list_main.30.78fd1802qp0XdF)
## Firmware
ZMK is what I use and have setup a shield for: [example config](https://github.com/grassfedreeve/zmk-config-akohekohe/) 
That being said the matrix is the same as a Hummingbird so you can use hummingbird firmware just fine on whichever firmware you enjoy.

## Inspiration & Thanks
- jcmkk3's [rufous](https://github.com/jcmkk3/trochilidae#rufous) hummingbird variation. Of which I used the Ergogen config, routing, and footprints.
- apfel's [ZilpZalp](https://github.com/kilipan/zilpzalp) keyboard
- PJE66's [hummingbird](https://github.com/PJE66/hummingbird) keyboard
- Weteor' [grumpy](https://github.com/weteor/Grumpy) and [fitis](https://github.com/weteor/fitis)
- apsu's [aptmak](https://github.com/apsu/aptmak) keyboard layout
