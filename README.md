<h1>Solenoids</h1>
<p>Solenoids are basically electromagnets: they are made of a big coil of copper wire with an armature (a slug of metal) in the middle. When the coil is energized, the slug is pulled into the centre of the coil. This makes the solenoid able to pull (from one end) or push (from the other).</p>

<p>The solenoids we have in hackSpace are nice and strong, they have armature with a return spring. This means that when activated with up to 24VDC, the solenoid moves and then the voltage is removed it springs back to the original position, which is quite handy. Many lower cost solenoids are only push type or only pull type and may not have a captive armature (it’ll fall out!) or don’t have a return spring. I think the great use of solenoid would be a bell in the vintage old telephones.</p>

<p>To drive a solenoid you will need a power transistor and a diode, check this diagram below for how to wire a solenoid to an Arduino. You will need a fairly good power supply to drive a solenoid, as a lot of current will rush into the solenoid to charge up the electro-magnet, about 250mA, so don’t try to power it with a 9V battery (it will simply not work). We found that two 9V batteries in series provided sufficient voltage to move the solenoid.</p>
 
