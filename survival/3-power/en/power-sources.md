# Chapter 3: Power

> To use the tools on your phone you need power. Power can also provide you with light and empower you in many other ways but the grid and outlets might not be available.

## Methods to generate power

### Solar

Solar USB chargers harvest the power of the sun - a great and very clean way to generate power. There are only 2 real drawbacks:

- Not available at night
- Output depends on weather

However, if it is available you can use it effortlessly. While harnessing the power of the sun you can engage in other actions such as obtaining food or building a shelter.

### Bicycle

Generating power with a bicycle is more effort but it can also serve as good exercise. Most bikes already have a dynamo installed to power lights. It can also charge a phone with a converter to 5V/USB.

### Improvised Generator

Almost any DC motor can generate electricity. Turn the motor by hand or other means and electricity will be generated at the (+) and (-) leads. The electricity produced will be in the form of AC, so a diode/rectifier is required to charge a battery.

The faster the motor turns, the higher the voltage produced. The current produced depends on the internals of the motor. Generally, the bigger and more difficult the motor is to turn, the more current it will produce.

**Motors that do not work for this are most fan motors and motors that do not have magnets in them. If the motor is magnetic without being plugged in, chances are it will work.**

### Wind

Wind-power is available day and night - but you need wind. Generators are often bulkier and hard to transport, but it can be a great option if you are not trying to move. It is not particularly difficult to build a wind-generator: get the wind to turn something, rotate a shaft, and attach a motor. A motor is basically the same as a generator - you just need to build some electronics to harvest the power.

### Water

Use the flow of a river. The same principle as a wind-turbine, but water rather than wind turns the generator. One big advantage of using a river is a steady rotation-speed, and the flow usually does not stop. However, it depends on having access to a river or a dam.

### Heat-Difference

Generate power by harnessing heat differentials, e.g. with a fire. There are portable campstoves and fire pots with USB power outlets. You can also harvest the power of a fire via steam, though on a small scale this is labor-intensive and hard to implement.

### Hand Crank

Small USB cranks operate by hand, some with a light or the ability to recharge standard AA/LR06 batteries. This binds you to the task, as you cannot do much else while turning. However, it is good to have an array of options.

### Car

Use a car or truck with a combustion engine. Cars come with an alternator that recharges the battery. Most car batteries are 12V. Convert the 12V to 5V for the phone using a voltage regulator or car USB charger. This is a wildly inefficient means to produce power, as the majority of the output powers the car itself. It is better to take advantage of this while driving to your destination, as the power is there anyway.

### Voltaic pile

Alessandro Volta invented the first electrical battery in 1799. Insert two pieces of metal into an acidic electrolyte. If the metals are copper (positive) and zinc (negative), approximately 3 cm apart and 3 cm squared, a tension of around 1V is generated.

To recharge a USB device, a pile of 5 cells in series is needed. Many fruits (lemons, oranges, grapefruits), vegetables (potatoes, plantain pith), or acid liquids (vinegar, grape juice, salt water) can serve as the electrolyte.

A pile of 5 lemon cells delivers 5V and around 1mA. The bigger the electrodes, the bigger the current. A one meter long gutter filled with sea water, with a copper hose inside, can produce 500mA.

Using a magnesium electrode instead of zinc makes a cell of 1.6V, allowing piles of only 3 cells.

As stated in Wikipedia, the energy comes from the chemical change in the zinc when it dissolves into the acid. The energy does not come from the lemon or potato. Cells will run as long as you have zinc and electrolyte. Avoid evaporation of the electrolyte.

### Aluminium-air cells

Industrially produced pure aluminium (soda cans, foils) allows more powerful cells, especially when paired with activated charcoal. A 10x10 cm cell with salt water electrolyte produces 1V and 100mA.

To make one: place a salt water soaked paper on aluminium foil, set a 1 cm charcoal layer on it, put a bare copper wire across the carbon, fold the foil like a burrito. The copper wire is positive, aluminium foil negative.

The drawback is that aluminium oxidizes within tens of minutes. The aluminium anode can be mechanically brushed or bleach can be added to the salt water to reactivate the cell.

## Tips & Tricks

### Power-Bank

Use a power bank to store energy while still generating it. Charge the power bank during the day and use it at night. **Be aware that capacity information on power banks is often inaccurate or outright lies. Test them yourself.**

Power banks are just batteries with standard plug interfaces (USB, 5V). Classic cellphone power banks use lithium batteries, which are best stored at 50% capacity. Recharge every 6 months.

### AC/DC Conversion

Converting AC to DC (rectification) is easy with a single component. Bridge rectifiers are marked with symbols '~ ~ + -'. Apply AC to the '~ ~' connectors and get DC from the '+ -' connectors.

Converting DC to AC (inversion) is much less efficient and requires a complex device (power inverter) that cannot be improvised.

### Save Power

Power not used is power that does not need to be generated. Phones consume more energy when radios (WiFi, Bluetooth, cellular) are switched on. Display brightness plays a big role in battery life.

**To save battery: low screen backlight, short screensaver timeout, airplane mode enabled.**

### Batteries

| Type | Typical Voltage | Rechargeable | Total Power | Current | Decay | Hazards |
|---|---|---|---|---|---|---|
| Alkaline | 1.5V (AA, AAA, C, D, 9V) | No | Moderate-low | Moderate-low | Slow | Non-hazardous |
| Zinc-Carbon | 1.5V (AA, AAA, 9V) | No | Very low | Low | Fast (decay unused) | Slightly irritating |
| Lithium Cell | 3V (coin, cylinder) | No | Moderate | Moderate | Very slow (15 yr shelf) | Fire risk if exposed to air |
| Nickel-based (NiCd/NiMH) | 1.2V (AA, AAA) | Yes | Moderate-low | Moderate-high | Very fast (die within month) | NiCd: very toxic. NiMH: safer |
| Lithium-Ion | 3-4.2V (18650, custom) | Yes | High | High (sometimes limited) | Slow (1+ yr) | Fire hazard, especially when charged |
| Lead-Acid | 6V, 12V | Yes | Moderate-high | Extremely high (car batteries) | Moderate (indefinite with trickle charge) | Lead (poisonous), sulfuric acid (burns) |
