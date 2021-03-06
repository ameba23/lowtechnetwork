Build a Pedal Generator from a Cycle-training stand!
====================================================

by Tim

Intro
-----

I first had the idea to build a pedal generator a long time ago when I
was at the Science Museum in London.. there was an exhibition where you
spun a stiff rotating bar round as hard as possible and if you were
strong enough a big bank of incandescent bulbs would light up in front
of you. That experiment was particularly depressing because it gave the
impression that a huge amount of physical energy was needed just to
power a few bulbs. In fact rather than that, it simply demonstrated how
inefficient incandescent lightbulbs are!

The reality is that a lot of electrical devices get by on a relatively
small amount of power. Anything powered by batteries will normally be
designed with low power consumption as a priority. Conversely, a lot of
items (though not all!) that run off the mains will be quite
power-hungry.

As a rough guide, a young person pedalling at a gentle rate, just about
breaking into a sweat can produce about 50 watts of power. If you were
pretty strong and really going for it you could probably generate 1000
watts for a bit, but that's not what we're interested in! It's far more
relevant to consider how much power you can produce steadily over a
longer time. If you were pedalling a bit harder and actually getting
some exercise, that would put out about 100 watts.

If you did that for an hour, you would have produced 100 w x 1 hour =
100 watt-hours of energy, or 0.1 kWh. Lets put that into perspective,
with 0.1 kWh, you can power a 20w (100w equivalent) eco-lightbulb or a
portable TV for 5 hours ..and it costs about 1p when drawn from the
mains!

If you're interested in how much a particular device uses, you can have
a look at the rated value on the back or bottom of the thing, however
they are often gross overestimates! For example, my alarm clock is rated
at 7w but draws less than 1w! Your PC power supply might be rated at
300w but it probably doesn't draw more than 100w.

If you're really interested, you could get hold of one of these meters
<http://www.maplin.co.uk/Module.aspx?ModuleNo=38343> (sometimes they are
on offer). It can give you a reading of the power consumption in watts
and if you leave it for a period of time it will report how much energy
has been used in kWh, amongst other things. It's given some surprising
results. Laptops vary enormously in their power consumption; I looked at
two friends' laptops, one used 20w when idle, the other 75w!

Note: if you plan to use one of these with a battery-powered inverter,
I'm not sure if it will work because it is probably designed to work
with a pure sine wave power supply, rather than the crude approximation
produced by an affordable inverter.

Generator designs
-----------------

This design is one of many you could follow. Each has its merits and its
drawbacks.

If you are after maximum efficiency and you have access to a lot of
tools and bits and box then you might want to consider making one David
Butcher's pedal generators:
<http://www.los-gatos.ca.us/davidbu/pedgen.html> however it's quite
bulky, which could be a problem for some! This guy is really passionate
about his pedal generator and the site is really comprehensive. It has a
lot of useful and interesting links about 12v equipment and it's really
worth a look.

If you don't have much spare cash, you could consider using an old bike
and an old car alternator to produce electricity, perhaps using these
comprehensive plans
<http://www.c-realevents.demon.co.uk/altgen/altpedgen.htm> However it's
probably the least mechanically efficient design around, with a lot of
energy lost through the belt transmission and in the alternator, which
itself is designed to be coupled to a car engine putting out 1000x as
much power as a cyclist!

For me, the design I chose was the clear winner. Here's the upside: the
design is relatively simple meaning that it's easy to make, quite
mechanically efficient and it can be disassembled and moved about
easily.

The only drawback is that it could be a little expensive. I'm afraid I
bought all new parts to make mine, because I had a very fixed idea of
what I wanted. I spent £76 on the training stand and £40 on the motor.
Depending on your means that could be a lot of cash to part with, it
certainly was for me but I was very determined to see the project
through! If you're patient, you can probably get a training stand a lot
cheaper on eBay, although they don't depreciate as fast as most other
things. You could also experiment with various 12 volt motors until you
find one that fits your setup and you never know it might come for free!

The idea for the design came from this website
<http://www.windstreampower.com/Human_Power_Trainer.php>

It's a commendable business despite that \$600 is very pricey for
essentially a training stand and a DC motor, but in their defence the
generator they use sells elsewhere on the net for somewhere around £200.
Why it's so expensive, I really don't know. Normally I would imagine
that you get what you pay for, but my £40 motor has a nearly identical
design and has been generating for more than a year now with no problems
at all.

Bike
----

One of the main advantages of this design is that you can use any old
road bike with a quick-release back wheel, just clip it in, adjust the
contact shaft height and pedal away. When you're done it just unclamps
out and you're ready to ride off straight away. No wires or belts or
fuss or anything like that.

The most important thing is to have a nice true wheel with flattish
treads on the tyres, like a road bike rather than a mountain bike with
big knobbly treads. I have heard that using a tyre in this way will wear
it down quite a bit faster than road use but in my experience it's not
that bad, just don't bother buying expensive new tyres for this project.

Cycle training stand
--------------------

Bicycle training stand. Cycling nutters use these things to train
indoors during bad weather. The best type is one which uses a contact
shaft and a flywheel with a separate kind of air or magnetic resitance
built in. Some stands don't have a flywheel but it pays to have a
flywheel as it moderates the pulses of power you put in to the system by
pumping away with your legs, and it allows you to store more energy for
starting up tricky devices like cathode ray tubes in TVs (more on that
later)

I trawled the net for a bit and settled on one of these

P00844\_BILD1GROSS.jpg

it is a "T1450 Cycletrack Speedbraker" made by Tacx. This is perfect
because its good for road bike wheels, it has a flywheel and screws to
position the contact shaft perfectly against the wheel with adjustable
pressure, something that would take absolutely ages of tinkering with a
completely "home-brew" design. A cheaper version (the T1400) is
available with a fan unit rather than a magnetic resistance, but I
didn't get one because I'm stupid.

Power plant - A 12v DC Motor
----------------------------

This is a trickiest part of the whole process. We are surrounded by all
sorts of motors, in vacuum cleaners, extractor fans etc but they almost
exclusively run on 240v AC power from the mains. That means we really
can't use them to charge a battery, and having one directly powering
something would be really quite complicated, dangerous and hardly worth
the risk. Fortunately, lots of 12 volt motors are available because
they're used to drive wheelchairs or lift loads on a pulley. A guy from
Bicycology used a windscreen wiper motor to charge their very
impressible impressive mobile cinema/stereo thingy (see
<http://www.bicycology.org.uk/what_we_do/energy_trailer.htm>) and
although using one of those would limit you to producing about 60 watts,
that's not so bad when you consider that you'll probably get puffed out
pedalling much harder than that anyway.

Important: obviously the shaft of the training stand needs to be coupled
to the motor shaft for the thing to work. It helps if they happen to be
the same diameter, because then you can probably get hold of a stock
part to couple them. See below.

The motor/generator needs to get up to and beyond 12v when you are
pedalling, in order to overcome the battery's 12 volts 'pushing' against
you.

In order to charge the battery, the motor voltage needs to go a bit
higher; a fully charged lead-acid battery reads about 12.7v and when
charging you want to be going at maybe a bit under 15v.

The complication is that when you spin the shaft of a '12v' motor, your
contacts won't read 12v immediately. There is a more or less linear
relationship between the rotation speed of the shaft (measured in
r.p.m.) and the output voltage.

So, for example, a motor will be rated to produce 1500rpm when supplied
with 12 volts with no mechanical load; It seems logical that if you do
the opposite and spin it round at 1500rpm you should get about 12v out
of it but in practise you would probably get about 9 volts.

If you are having trouble finding a motor, try
<http://www.motioncontrolproducts.com> and look at their surplus stock
section as you’ll probably find something suitable. My motor came from
this company via eBay and I’m pretty satisfied with what I got.

Maths
-----

At this point, if you are going to invest any real money in a motor it's
worth doing the maths before you part with your money. You need to make
sure that when the thing is assembled the speed that you're pedalling at
roughly matches the motor's rated rpm. In reality, and particularly if
your bike will has lots of gears, it doesn't matter too much if the
numbers are a bit off.

If we choose a target voltage of 15v and use the motor rating I
mentioned before (1500rpm at 12v and vice-versa) - thats 9 volts
produced by 1500rpm when you are using the motor as a generator.

Then to get 15v out of the generator, we need to acheive a rotation
speed of (15v/9v) x 1500 rpm = 2500rpm. (a lot of motors can be driven
above their rated rpm or voltage, within reason)

The circumference of an average road bike wheel is about 210cm, the
circumference of the contact shaft on the T1450 is 16cm so for every
wheel turn the shaft is turning 210cm/16cm=about 13 times. If we want
the shaft to turn around 2500rpm then the wheel needs to turn
2500rpm/13=192rpm

192rpm x 2.1m tyre circumference = 404 metres /min which is roughly 15
miles an hour - a perfect cycling speed!

If this has made you a little hesitant, then don't worry: As long as you
don't have to spin the motor really fast (much faster than it is
designed to spin) in order to generate 13-15v, it should be fine.

Having got hold of the right motor, the most taxing part of the whole
process is over!

Supporting the motor
--------------------

Depending on the weight of your motor, it might need a lot of support.
My motor weighs nearly 10Kg and it would probably snap the whole
assembly if I just left it unsupported. The best way I found to hold it
in place was to sit it on a piece of wooden shelf. That gives you a
nice, flat surface to support it. To hold it in place, I used a few
cable ties strung together over around the motor and the shelf, with
some old inner tube rubber to dampen the vibrations. See the pic:
motor.jpg

Whenever I set up the generator, I have to support this shelf with some
foam or a few towels, so that it is comfortably sitting there at the
same height as the flywheel and contact shaft. If its just hanging
there, or not supported properly then you are going to damage the
innards of the motor.

It would be better to have some kind of adjustable supports (for examle
a bolt at each corner of the wood base, with two nuts to hold the base
at the correct height).. but I haven’t got round to that yet.

Instructions
------------

Looking back, making this design is surprisingly simple. Basically all
you have to do is attach the two shafts and then all that follows is
some elementary electronics.

Basically all we have to do to prepare the stand is to tear off the part
that provides resistance. Mine was in a sealed housing so I just took to
it with a hacksaw and pliers and yanked it all off to reveal a nice
clean 10mm shaft, see pic: shaft.jpg

Now, you need to find a way to couple the shaft of the training stand to
your motor. This could be easy, or it could be very difficult.

I didn't have much foresight and I ended up with one shaft being 10mm
and the other 11mm. I didn't think this would be such a problem but I
couldn't find anything mass-produced which would couple them. In the end
I had to get a sort of 'sleeve' machined for me by the kind guys in the
mechanical workshop at Leeds Uni. It's basically a cylinder of High
Speed Steel with a 10mm and 11mm hole bored down the central axis either
side, with grub screws along the length of the sleeve to secure the two
shafts in place. It took them about 5 minutes to make and luckily they
did it for free as I was a student, but I expect that it wouldn't be
very cheap if you had to have one machined for you! If you are stuck at
this point, it could be worth visiting a school or uni with a good tech
department. Many of them are willing to make something like this if you
provide a clear diagram although you will probably have to negotiate a
price. The shafts have to line up precisely so there is no way that you
could make one yourself, unless you have a lathe! Here's my working
set-up with the coupling pointed out: part.jpg

If you've got hold of a windscreen wiper motor, there is another
possibility. The guy from bicycology had done away with the cycle
stand's friction wheel and flywheel and just made a wooden insert to
take its place. He searched high and low and eventually found a plastic
wheel to fit the motor shaft which was also about the right diameter
(about an inch) to go with the wheel. Here's a picture. bikology.jpg

Having got the shafts coupled, you're nearly there!

Batteries
---------

This is where you will need your multimeter! You might be tempted to run
your equipment directly from the motor, but this is a VERY BAD IDEA! The
power coming out of the generator is too variable – as you are pedalling
the voltage rises and falls and is unlikely to be close enough to 12v to
suit the equipment. I found this out the hard way when I connected my
generator directly to an inverter to try and power a TV. As I pedalled
like mad to get the TV started, raising the voltage way above the max.
15v the inverter was rated for. There was a huge bang and awful smell
from the inverter. I had basically destroyed most of the components
inside – the capacitors had vented their electrolyte everywhere and
there was no way to save it!

Fortunately, the simple solution is to fit a battery into the circuit it
smoothes the spikes in voltage and maintains it relatively close to 12v.
The same principles apply in cars - if you disconnect the battery while
the engine’s running you’re likely to damage all the sensitive
electronics like the stereo.

The size of battery depends on what you are planning to use the
generator for. If you mostly want to power things directly, you could
probably get away with a cheaper 7 Amp Hour battery. If you only want to
power devices directly, you could look into using a 'supercapacitor'
(with capacitance &gt; 50 Farads rated for 15v) as a way to smooth out
the power. If that sounds interesting, check out David Butcher's website
above.

Note: 7 Amp Hours (normally abbreviated to Ah) means that the battery
can store enough energy to power a load of 7 Amps for an hour, however
you wouldn’t want to do that because running a Lead-acid battery down to
below a 50% charge considerably shortens its lifespan.

A car battery (with about 40 Ah of capacity) is an alright option- it
might power some audio equipment for a few hours. But it will quickly
degrade and lose capacity if you are charging and discharging it often.
If you are planning to do big long pedalling sessions and run it down
over long periods then you need a battery with a higher capacity. These
batteries are called leisure batteries because they’re used on caravans,
narrowboats and the like. They can store enough power for a few days
worth of use and are much more resilient to deep discharges than car
batteries (which are really only meant to give a 1-second jolt of high
power)

Unfortunately lead-acid batteries aren’t very environmentally friendly
(being full of Lead and Sulphuric acid) but there isn’t any real
alternative. Other battery technologies like NiCd and NiMh have a
significantly higher internal resistance and so more of your energy is
lost as heat when you are running equipment from the battery.

By the way, it’s an inevitable fact that you don’t get as much back
energy back out from the battery as you have put in. Quite a bit is lost
as a result of chemical processes taking place in the battery when it is
charged and while it is stored. This equates to a coulometric efficiency
of about 70% for lead-acid batteries but this is dependent on
temperature and highly dependent on the speed that you are charging at.
That means that it’s more energy efficient to generate the power for the
equipment while it’s being used, and that might be a consideration for
some of your devices.

Electronics
-----------

Assuming you have used a 12 volt DC motor, there should be two
terminals. To connect the motor properly, spin the shaft the same way
that it will travel when it’s attached to the training stand with the
probes from the multimeter attached to the terminals any way round. You
want the multimeter to read a small positive voltage, if it does then
the terminal the red probe is connected to is the positive one (and the
terminal with the black probe is the negative) if you read a negative
voltage then swap the probes around. generator-1.jpg Having discovered
which terminal is which, make a mark on each so you don’t forget!

The wiring needed is really very simple, you more or less just directly
connect the terminals but obviously it’s not that simple because as soon
as you connect the motor and battery it will start spinning (this looks
really weird) You need to put a diode in the circuit to stop current
flowing that way (driving the motor) but allows current to flow the
opposite way (charging the battery or powering something).

A diode is a pretty standard part that you can normally get individually
at a Radio Shack or Maplin. Make sure you get one that can handle larger
currents of several Amps. The one I use is designated \[6A80\] for 6
Amps and it has worked fine for me.

Technical note: In fact you only really need the diode in the circuit
while the generator is idle or otherwise generating under 12v. When you
start pedalling, for a few seconds you are working to overcome the
voltage of the battery (and the diode is preventing current from flowing
the wrong way) once you are up to a good rpm and the generator voltage
has risen above the battery voltage, then current begins to flow and you
are charging. Since current is flowing through the diode (in the allowed
direction) some energy is being lost as heat and causing a voltage drop.
The diode is basically just a piece of silicon so not a totally ideal
conductor. This amounts to about 5% drop inefficiency. If that bothers
you could install a switch to bypass the diode, which you would activate
while you are pedalling at speed (and disengage before you stop
pedalling). However the extra length of wire and the connections within
the switch will introduce a small voltage drop of their own, so whether
it’s worth the hassle is debatable.

This is how the wiring should look, I think the diode is the correct way
round but it’s quite simple to work out yourself. Be careful not to
connect the diode the wrong way round – if the motor runs you may well
damage the diode as the current will probably exceed the rated maximum.

generator-2.jpg

Try to use thickish wire because it has less electrical resistance. When
using devices at 12v the current is relatively high and so more energy
is lost to heat (due to resistance) than with 240v wiring on the mains.

It’s also a good idea to hardwire in a multimeter to the battery
(perhaps use a connector block) so that you can keep an eye on the
voltage. When you start pedalling the voltage should stay static at the
battery’s voltage but as you get up to speed, it will rise and fluctuate
a bit above the battery voltage. As you charge the battery to nearly
full, the voltage will be getting higher. You don’t really want to go
above 14.4 volts, especially on a smaller battery as it will shorten the
battery’s life.

It’s difficult to tell when a battery is full and you will have to use
your judgement. After you have just been through a charge the battery is
not at rest so the multimeter readings are not reliable. The easiest
reliable way to test the 'state of charge' is to measure the resting
voltage at least 3 hours after the battery was last charged/discharged
and compare it to this graph: soc.jpg Note: When you start pedalling,
try to get up to speed quickly as to begin with you are pedalling
without a load which can damage the magnets inside the motor.

Powering stuff
--------------

As I said, you can power things from the battery while you are resting,
or directly while you are pedalling (although you should keep the
battery attached)

The fantastic advantage of using a 12 volt generator/battery is that
there is a lot of equipment designed to take 12 volts. Anything that
will plug into a cigarette lighter socket will work fine, you can get 12
volt refrigerators and TV sets and there are also fluorescent bulbs and
LEDs bulbs that run on 12v. I think the most useful thing you can get
hold of is an inverter which takes the 12 Volt DC and converts it to a
good approximation of 240V AC mains electricity and gives you a socket.

I’ve powered PCs, laptops, a TV, audio equipment, lighting and charged
batteries with this (so now my mp3 player is pedal powered too)

It’s pretty cool to be watching TV using energy you are providing
yourself. Just imagine how different society would be if you had to
pedal for an hour to watch an hours TV - there wouldn’t be any obesity
and almost everyone would be super fit!

The reality is that it would be very difficult to provide all of your
electricity this way. I’ve spent about five hours writing this guide on
my PC, in order to produce the electricity I have used in that time, I
would have to pedal for about 20 hours! Even with everything switched
off in my house, it still seems to draw 100-200W which is way more than
the 50W you can comfortable produce continuously.

I think this makes the point that in order to reduce our impact on the
environment we don’t just need to increase the use of renewable sources
of electricity or switch things off, we need all of our devices to be
designed as energy efficient as possible.

Pitfalls
--------

Don't use thin wires to connect the motor and the battery because the
high currents will create a lot of heat, wasting energy and quite
possibly melting your wires. Even the relatively thick leads you get
with inverters are often rated for just 10 Amps.

As I mentioned above It's a bad idea to pedal the generator to power
something if the battery is not connected. You can easily go above the
safe voltage for a piece of equipment and destroy it. Also the power
supplied by pedalling isn't uniform, it fluctuates up and down with the
pedalling strokes making it unsuitable for most equipment.

Take care not to allow the current to exceed the rated current for the
diode. It's relatively sensitive and if it breaks down you might find
the battery motoring your bike wheel around!

Another thing to avoid is pedalling the generator without anything
attached. I've heard that this causes the permanent magnets in the motor
to demagnetise, rendering it useless!

Obviously it goes without saying to be careful not to short circuit the
terminals of the battery! With all the wires and bits of metal around
this can be surprisingly easy and very dangerous. If you're not very
confident of wiring up the circuit, you might want to put a fuse in
line, in case you make a mistake.

Improvements
------------

The biggest problem left with this design is to provide support for the
motor. Like I said, It's really heavy and it needs something to support
it. I put it on a wooden platform and secured it in place with cable
ties. At the moment when I want to use the generator I put a pillow or
some towels under the platform but it would be better to actually drill
some nuts and bolts in to give it some adjsutable supports.

Updated August 2008. Retrieved from wayback machine (archive.org) 2015
