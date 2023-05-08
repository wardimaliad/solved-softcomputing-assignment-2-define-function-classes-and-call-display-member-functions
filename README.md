Download Link: https://assignmentchef.com/product/solved-softcomputing-assignment-2-define-function-classes-and-call-display-member-functions
<br>
Define Function Classes and Call Display Member Functions

<ul>

 <li>Analyze the data structure of the functions defined in the last assignment. Wrap up each function with a C# class. Define parameters as a private array of double type. In addition, define the list of</li>

</ul>

parameter names as a public static array of string type. Note that the t() is a Triangle function, g() is a Gaussian function, and b() is a Bell function. Therefore, name parameter names of each class meaningful names; e.g., Left, Peak, Right for parameters <em>a</em>, <em>b</em>, <em>c</em> of the TriangularFunction.

<ul>

 <li>Define a public function (method) for each class to return the function value for a given value of <em>x</em>. E.g., public double GetFunctionValue( double <em>x</em> );</li>

 <li>Define a constructor for each class to let user initialize the parameters.</li>

 <li>A ListBox object lists the type names of the implemented function classes to let user to select a</li>

</ul>

function type to dynamically create and display a function object. Alternatively, a number of RadioButton objects can serve the same functionalities. When a target type is selected, the UI controls should be updated (hide or show) for the user to specify parameter values.

<ul>

 <li>Change the code in button-click event handling function to create a function object and display its line by calling the GetFunctionValue() method of each object of function class. When a function object is new-ed, a series object is run-time added to the chart object (via its Series property). Since objects of these functions are dynamically created, how can we change their parameter values and update their line displays?</li>

 <li>In addition, add a new function class to deal with the following function (Sigmoidal function): sig(<em>x a c</em>; , )=</li>

</ul>




<ul>

 <li>Prepare a folder named as &lt;your ID&gt;&lt;your name&gt;Ass02 to put your source code in it. Compress the folder of your source code into an RAR or a ZIP file and submit to COOL. Remember to add as many comments as possible in your source code.</li>

</ul>




Notes:

<ul>

 <li>Exercise the uses of the following controls (primary properties and events):</li>

</ul>

NumericalUpDown, TrackBar, ComboBox, ListBox

<ul>

 <li>Think about how to specify the title, range, and resolution of the <em>x</em>-axis as a class to serve for these function objects.</li>

 <li>Think about how to deal with the line charts (object of Series), which of them seems belong to each object of the function class.</li>

</ul>