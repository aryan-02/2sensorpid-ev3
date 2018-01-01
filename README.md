# Dual-Sensor Proportional-Integral-Derivative Line-Follower Algorithm for Lego Mindstorms EV3

## Hello World!

## Here's how to use this:

<ol>
	<li>Download and extract the files from this repository, or clone this using <code>$ git clone git://github.com/aryan-02/2sensorpid.git</code>
	</li>
	<li>
		Before you import the My-Blocks, open the project properties, click "Variables" and create the following variables:<br><br>
		<table>
			<thead><tr><td>Variable Name</td><td>DataType</td></tr></thead>
			<tr><td>Error</td><td>Numeric</td></tr>
			<tr><td>Integral</td><td>Numeric</td></tr>
			<tr><td>Derivative</td><td>Numeric</td></tr>
			<tr><td>kP</td><td>Numeric</td></tr>
			<tr><td>kI</td><td>Numeric</td></tr>
			<tr><td>kD</td><td>Numeric</td></tr>
			<tr><td>l_Error</td><td>Numeric</td></tr>
		</table>
	</li>
	<li>
		Import both the My-Blocks (init and PID).
	</li>
	<li>
		Right after the start block, put the init my-block.
	</li>
	<li>
		Now, put the PID my-block inside a loop. Add two Color Sensor blocks with mode set to Measure -> Reflected Light Intensity, set the ports for your left and right color sensors respectively. Now, plug in the left and right sensor values into their respective input slots (leftSensorValue and rightSensorValue).
	</li>
	<li>
	Next, Set your power, kP, kI and kD
	</li>
</ol>

And you're done.

## Here's how to contribute to this repository:

Fork the repository, make the changes. Make sure you commit your changes and mention what you've improved. Then make a pull request. If the changes are approved, they'll get merged into this repository.
