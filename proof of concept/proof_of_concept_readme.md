# simple-fermentation-box:
## the $165 plug-n-play fermentation incubator
a super simple, no wiring required, controlled environment in which to incubate fermentations

you: want to make koji, or keep a miso or a lactic fermentation in a precise environment for better stability and reproducibility; but you don't want to spend a lot of money and don't have time to teach yourself how to wire a PID box right now. 

This is a 30-minute project to make a quick-n-dirty, plug-n-play incubator.

Senses: Temperature, humidity
Actuates: Heating, humidification

*The housing:* an 18" x 26" x 12" lexan container (made by cambro) with lid. Found in restaurant walk-ins the world over. Food-grade, rugged, easy to clean.

*The controller:* the most expensive component. Not truly a PID box (this is a thermostat, it works on a different algorithm; in truth, the algorithm is turn the actuator on when the setpoint is too low and turn it off when the setpoint is reached.) PID controllers are great! I highly recommend them. But since they involve wiring a temperature sensor and heating actuator, they are beyond the scope of this design. 

*The heater:* waterproof, even heating. Not as nice as circulating heated air, but it works.

*The humidifier:* a cheap and cheerful humidifier, designed for running in your car or at your desk. Works nicely in a small space.

*The insulation:* don't use a styrofoam cooler, they are hard to clean and they tend to off-gas when heated. They can melt in contact with a heating element. Instead, use Reflectix, a nifty, thin, flexible insulation to make a jacket for your lexan housing.

**Directions:**

make a jacket for the lexan (#1 on BOM) out of reflectix (#8 on BOM) and reflective insulation tape (#9 on BOM). Fit at least the sides, or sides and bottom, if you want to be more precise. I usually trim the reflectix to the height of the food storage container, and cut this to a little sider than each side, then overlap the ends and tape to fit the sloping sides of the container. Cut another piece that fits the lid. Don't tape the reflectix directly to the plastic housing, so that you can remove the jacket as necessary.

unroll the heating mat (#5 on the bill of materials (BOM)) and put it in the bottom of the lexan container (#1, cambro polycarbonate food storage box, on BOM). Put the drain trays (#3 on BOM) on top of the heating mat. Put the humidifier (#6 on BOM) inside the box as well. Fill it with water, insert a wick into the cap, and cap it, first.

Plug in the humidity and temperature controller (#4 on BOM) and plug in the heating mat and humidifier (using the USB cable and USB to AC adapter). Set the temperature and humidity to your desired range.

For koji, try 32C and 85% humidity.

put the temperature and humidity probe on the surface of the substrate you're going to ferment. This size box can hold 2-3 half size perforated hotel pans for incubating koji. Put the probe inside the inoculated koji of the lowest tray. This one will get the most heat, so rotate the position of trays in the stack every 4 hours (you can take a break when you're sleeping). 


