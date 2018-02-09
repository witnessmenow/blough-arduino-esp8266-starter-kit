# DIY Arduino Starter kit using an ESP8266

This is a guide for buying a really cheap kit for getting started with Arduino's that will allow you to build some pretty cool starter level projects that interact with different sensors and displays that you can control with your phone or computer via WiFi. 

Rather than just having examples of how to use each sensor/module I will instead provide instructions on how to build small projects with them, as I think this is would be a more enjoyable way to learn. 

For example, instead of showing example code for getting the soil moisture sensor working, I'll provide instructions on how to build a project that measures soil moisture of your plant and sends you a tweet when it needs to be watered!

## Why Did I Make this List

I see the question online a lot: **What kit should I buy to get started?** 

The answer is usually something like an [Elegoo Uno starter kit](http://amzn.to/2H33WdV). While I think these kits are decent, there is two main reasons why I would recomend this DIY kit instead

1) **I think the ESP8266 is a way more insteresting board than an Arduino Uno** - It can do basically everything an Uno but it has built in WiFi. This means it can connect to the internet to send/recieve data which I think makes for way cooler projects! The WiFi features are not hard to use and it really expands what you can do with your board. The Uno does have some advantages over the ESP8266, mainly that it has more pins, but for starter projects this often isn't an issue.
2) **It's much cheaper** - If you go for the cheapest way to buy this kit it is less than $15 delivered, which is $20 cheaper than the basic Elegoo kit. In my opinion the components and displays in this kit are better suited to start building actual funcitoning projects than with other starter kits, which focus on giving you different components that might make up a project.

## Buying The Kit

Below you will find links to buying the different parts of the kit from Aliexpress. I find that Aliexpress is the cheapest place to buy this kind of stuff and I almost use it exclusively when buying parts for my projects. Do note that it typically  takes 2-4 weeks for packages to arrive (and could even be more in some countries)

To be able to do all the projects that I will cover you will need to buy all the parts listed in **Board and Modules** section and you will need to pick one of the options in the **Basic Components** section.

### Board & Modules

There are the main parts that we will be using for the projects.

| Part        | Cost           | Description  |
| ------------- | -------------:| ----------------|
| [NodeMCU ESP8266 Development Board (CP2012 version)](http://s.click.aliexpress.com/e/BQBAIYj)| $3.05 | This ESP8266 has everything you need to just use (once you have the software setup. There are other NodeMCU boards that are a different size that don't fit in breadboards, which would be best to avoid! |
| [Soil Moisture Sensor](http://s.click.aliexpress.com/e/BUVbUzZ) | $0.53 | Can be used to check if a plant needs to be watered |
| [PIR Motion Sensor](http://s.click.aliexpress.com/e/EeiYzVb)| $0.78 | Can detect when a person is nearby |
| [0.96" OLED Display](http://s.click.aliexpress.com/e/AiqJeq7)      | $2.24      |   This is a really nice crisp display that only requires 4 pins to use |
| [4 Digit Seven Segment Display](http://s.click.aliexpress.com/e/qfM3Jei)| $0.77 | Can be used as a clock or to display any numbers |
| [LDR Module](http://s.click.aliexpress.com/e/nMrBiiE)| $0.37 | Can be used to detect differences in light levels |
| [Buzzer Module](http://s.click.aliexpress.com/e/AAq7YJQ)| $0.29 | Can be used to play different tones |
| [DHT11 Temperature & Humidity Sensor](http://s.click.aliexpress.com/e/qr3RRNf) | $0.99 | For getting the temperature and humidity |
|[HC-SR04 Distance Sensor](http://s.click.aliexpress.com/e/N7MRvFa)| $0.78 | Can be used to measure the distance from the sensor to an object |

### Basics Components

This is the LEDs, resistors, buttons, wires and other parts that will be used to connect the sensors and the board together. I'll provide two options:

#### Options A: Cheap and cheerful

Is the cheapest kit I could find but it won't cover doing much other projects outside the ones listed here. I've found the breadboards that come with this kit to be pretty poor, but have been usable (just very stiff)

| Part        | Cost           | Description  |
| ------------- | -------------:| ----------------|
| [Basic starter kit](http://s.click.aliexpress.com/e/RFU3Z33) | $2.42 | Contains a breadboard, LEDs, buttons, jumper wires and resistors.|
| [100PCs 2N2222 Transistors](http://s.click.aliexpress.com/e/YfQNfmy)| $0.99 | We actually only need one, but I didn't see any smaller packs!|
| [40Pcs M-F Jumper Wires](http://s.click.aliexpress.com/e/N7AQ7YN)| $0.65 | Can be used to connect displays and modules to the breadboard.|

#### Options B: Complete Kit

Is a more complete kit for someone looking to get started with Arduino. It should cover a lot of the basic components that are required for most Arduino projects. It might even be worth picking up this list of stuff after option A if you think you'll continue on with Arduino

| Part        | Cost           | Description  |
| ------------- | -------------:| ----------------|
| [Good Solderless Breadboard](http://s.click.aliexpress.com/e/fufyjMv)| $1.78 | This is pretty close in price to the basic starter kit which includes a breadboard, but I have found these to be very good quality. You can buy cheaper ones (around a $1 each) but do yourself a favour and spend the extra few cent!|
|  [300PCs Resistor Set](http://s.click.aliexpress.com/e/qNBaAE6)| $1.57      | A huge range of resistors that should do you a long, long time |
| [100PCs LED Kit](http://s.click.aliexpress.com/e/eyRRBA2) | $0.90 | 20 each of Red, Green, Blue, Yellow and White Leds |
| [10PCs Tactile button kit](http://s.click.aliexpress.com/e/6uv7QNj) | $0.40 | Comes with plastic caps as well |
| [200PCs Transistor Assortment Kit](http://s.click.aliexpress.com/e/3fuZFQ3) | $2.56 | 20PCs of 10 different transistors in a plastic box |
| [40Pcs M-M Jumper Wires](http://s.click.aliexpress.com/e/BiujMFu)| $0.65 | I recomend buying a few packs of these. It will be used to connect things together on the breadboard.|
| [40Pcs M-F Jumper Wires](http://s.click.aliexpress.com/e/N7AQ7YN)| $0.65 | Can be used to connect displays and modules to the breadboard.|
