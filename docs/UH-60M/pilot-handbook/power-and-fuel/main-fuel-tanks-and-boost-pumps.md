# Main Fuel Tanks and Boost Pumps

The two main tanks have separate quantity indications. On EICAS, **1** is the left tank and **2** is the right tank. **TOTAL** is the fuel weight MSFS reports for the aircraft. The fuel figures on this page are in pounds.

## Reading the quantities

The display rounds each tank down to the nearest five pounds and does the same to the total. For example, if MSFS contains 208 pounds on the left and 209 on the right, the individual indications read **205** and **205**, while **TOTAL** reads **415**. The difference comes from rounding each number separately.

The colored bars have a maximum height. At higher loads you can change the quantity in the fuel menu and see the number change while the bar stays full. Read the figures when comparing the two sides. **FUEL 1 LOW** and **FUEL 2 LOW** are driven by the weight in the respective tanks. Adding fuel only to the right tank will not clear a left-tank quantity caution.

## Fuel controls on the overhead panel

| Control | How to recognize it | What it controls |
| --- | --- | --- |
| Engine fuel selectors | Tooltips include **ENG1 FUEL** or **ENG2 FUEL**, followed by **OFF**, **DIR** or **XFD**. | The selected engine's feed setting. **DIR** means direct feed and **XFD** means crossfeed. |
| Engine boost pumps | Two switches with **ENG1 BOOST PUMP** and **ENG2 BOOST PUMP** tooltips. | Individual electric pumps. EICAS reports their switch states as **BOOST PUMP 1 ON** and **BOOST PUMP 2 ON**. |
| APU boost | A separate three-position fuel pump selector with a **PRIME APU** tooltip in its APU position. | The APU pump on the left main tank's supply line. |

An engine boost-pump advisory tells you the switch is on. Quantity is a separate indication, and neither boost-pump switch transfers fuel to the other tank. If you're trying to reproduce a fuel problem in the sim, note the left and right quantities, each selector position and the numbered boost-pump advisories. Two aircraft with the same **TOTAL** can have very different fuel distributions.

[H-60 systems source](https://github.com/Delta-Simulations/MSFS-H-60M/tree/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60)
