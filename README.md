<h1>Agricultural development</h1>
<h2>Overview</h2>
<p>A project in IOT that senses gases emitted from the tractor using gas sensors MQ135 and if the emission value is more than the threshold a value it sends it to the cloud (THingspeak)<p>
<h2>Components</h2>
<li>MQ135 gas sensor</li>
<li>Node mcu</li>
<li>1.2v battery</li>
<li>Jumpers</li>
<h2>Modification</h2>
<p>1.Alongwith the gas sensors we are using the lm35 temperature sensor
     to measure the temperature of the engine and send that data to thingspeak
     as well.
     This will help us in monitoring the temperature variations of the engine
     and further in analysing the emission of harmful gases.
     </p>
<h3>Expected Advancements</h3>
<li>#we are thinking of using the pressure sensors to measure the tyre pressure so that 
      the person gets to knows that the pressure is too low that it can get puntured and can
      take action likewise</li>
<li>#We also plan to send all these data to thingspeak and take an automated action once the threshold is broken</li>
