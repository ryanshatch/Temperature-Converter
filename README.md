<h1>Temperature Converter</h1>

<h4>The Temperature Converter is a C++ program that reads temperature data in Fahrenheit from a file, converts it to Celsius, and saves the converted data in another file. It provides a simple way to convert temperature readings for multiple cities from one unit to another.</h4>

<h2>Features:</h2>

<ul>
  <li>Read temperature data in Fahrenheit from a file.</li>
  <li>Convert Fahrenheit temperatures to Celsius.</li>
  <li>Save the converted data in a file.</li>
</ul>

<h2>Getting Started:</h2>

<p>To use the Temperature Converter, follow these steps:</p>

<ol>
  <li>Clone the repository or download the source code files.</li>
  <li>Open a terminal or command prompt and navigate to the project directory.</li>
  <li>Compile the source code using a C++ compiler:</li>
</ol>

<pre><code>g++ temperature_converter.cpp -o temperature_converter
</code></pre>

<ol start="4">
  <li>Run the executable:</li>
</ol>

<pre><code>./temperature_converter
</code></pre>

<p>The program will read the temperature data from the "TempInFarenheit.txt" file. Make sure this file exists in the same directory as the program.</p>

<p>The program will display the yearly averages of temperatures in Fahrenheit for each city.</p>

<p>Press Enter to convert the temperatures to Celsius.</p>

<p>The program will convert the temperatures and save the converted data in the "TempInCelsius.txt" file.</p>

<p>Check the "TempInCelsius.txt" file to view the converted temperatures.</p>

<p>Close the application when you're finished.</p>

<h2>Requirements:</h2>

<ul>
  <li>C++ IDE/Compiler</li>
</ul>

<h2>Example Output:</h2>

<pre><code>Yearly averages in Fahrenheit are:

New York 75
Los Angeles 85
Chicago 65
Houston 90

Press Enter to convert to Celsius.
</code></pre>

<p>After pressing Enter:</p>

<pre><code>The temperatures in Celsius have been saved in "TempInCelsius.txt" file.
</code></pre>

<h2>File Format:</h2>

<p>The input file ("TempInFarenheit.txt") should contain temperature data in the following format:</p>

<pre><code>City1 Temperature1
City2 Temperature2
City3 Temperature3
...
</code></pre>

<p>The output file ("TempInCelsius.txt") will contain the converted temperatures in Celsius, with each line following the format:</p>

<pre><code>City1 Temperature1
City2 Temperature2
City3 Temperature3
...
</code></pre>

> Please note that the example output and file formats are based on the provided input values.

<h2>Conversion Formula:</h2>

<p>The program converts Fahrenheit temperatures to Celsius using the formula:</p>

<pre><code>C = (F - 32) * 5 / 9
</code></pre>

<p>Where <code>C</code> represents the temperature in Celsius, and <code>F</code> represents the temperature in Fahrenheit.</p>

<h2>Error Handling:</h2>

<ul>
  <li>If the input file ("TempInFarenheit.txt") cannot be opened, the program will display an error message and exit.</li>
  <li>If the output file ("TempInCelsius.txt") cannot be opened, the program will display an error message and exit.</li>
</ul>

<p>It is essential to ensure that the input file exists and the program has proper read and write permissions in the directory.</p>