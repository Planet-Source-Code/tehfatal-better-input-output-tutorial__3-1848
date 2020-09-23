<div align="center">

## Better Input/Output Tutorial


</div>

### Description

Just a quick Article on Input/Output, since the last artical on input/output was done by a beginner. And sucked bad....lol, sorry dude. Please take a second and vote on this example, thanks.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[tehfatal](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/tehfatal.md)
**Level**          |Beginner
**User Rating**    |3.0 (12 globes from 4 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__3-32.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/tehfatal-better-input-output-tutorial__3-1848/archive/master.zip)





### Source Code

<font face="Verdana, Arial, Helvetica, sans-serif" size="6" color="#CC0000">Input
 / Output Tutorial<br>
 <b><font size="3">Writen by fatal</font></b></font></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">This
 tuturial is writen for beginer to the c++ language, first off to the beginer
 of c++. The most common error is forgeting the semi-colin at the end of each
 line. But theirs an exception to this, when using loops( ie: for loop, do/while
 loop, & while loop) you dont put a semi-colin at the end</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">ex:<br>
 for( x=1; x<8; x++)<font color="#FF0000">;</font><br>
 {<br>
 cout<< x << endl;<br>
 }</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">If
 you add the semi-colin it will ignore the cout command and continue with the
 program. That the only time where you dont put the semi-colin.</font></b></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="6" color="#CC0000">Input</font></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">When
 you input an integer, char, or arrays. You will be using the cin command.<br>
 Syntax:<br>
 cin>> <i>varible_name</i>;</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">this
 will take the inputed data and store it to the varible. Arrays are different
 story tho, to make an input to a char array, you have to use cin.get and cin.ignore.</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">Syntax:<br>
 char array[21]; // Declare a char array</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">cin.get(array,
 21); // we do this instead of cin because it can store everything ex: fatal
 is god</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">cin.ignore(80,
 '\n'); // This is to clear the stream</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">Its
 better to use cin.get than cin, because cin will store everything up to a space,
 but cin.get will store everything you input like Jane Doe. cin would just sote
 Jane if you inputed Jane Doe.</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">Other
 than storing to arrays, just using cin for numbers and charactors will be fine.</font></b></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="6" color="#CC0000">Output:</font></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">To
 output all it is, is using cout. <br>
 Syntax:<br>
 cout<<"Hello World";</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">Say
 you want to output an interger:<br>
 Syntax:<br>
 int x = 8;</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">cout<<
 x << endl;</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">Or</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">cout<<"My
 Integer: " << x << endl;</font></b></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">Since
 outputing is very simple, thats all i will explain.</font></b></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="6" color="#CC0000">Puting
 it all together...</font></p>
<p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">Heres
 a simple program using everything that I explained in this tutorial:</font></b></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">#include
 <iostream.h> // Needed for the cin, cout, cin.get, and cin.ignore</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">int
 main() // Start of main function<br>
 {<br>
 int x;<br>
 char i;<br>
 char array[21];<br>
 char array2[21];</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">cout<<"Enter
 in a Integer: "; // Using cout to give user instructions<br>
 cin>> x; // Storing the inputed number to x</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">cout<<"The
 Integer Inputed is: " << x << endl; // Outputing what the user
 inputed</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">cout<<"Enter
 a single charactor: "; // Asking user to input a charactor<br>
 cin>> i; // Storeing the charactor to i</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">cout<<"The
 Charactor Inputed is: " << i << end;// Outputing what was inputed</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">cout<<"Enter
 in your full name: ": // Asking user for their full name<br>
 cin>> arrray;// Storing full name to array</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">cout<<"Your
 Full Name is: " << array << endl;<br>
 // As you will notice it will only output everything up to the space</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">cout<<"Enter
 in your full name again: ";<br>
 cin.get( array2, 21); // Gets everythin that was inputed<br>
 cin.ignore(80, '\n'); // Clears stream</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">cout<<"You
 full name is: " << array2 << endl;<br>
 // Notice how you full name is outputed this time<br>
 </font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">return
 0; // Tells the complier that you program is done</font></p>
<p align="left"><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#666666">}</font></p>
<p align="left"> </p>
<p align="left"><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666">Now
 I hope that cleared up your confusion on input/output. In my opinion this is
 a great tutorial on input/output, and i hope it was good enough to help you.</font></b></p>
<p align="left"><b><font face="Verdana, Arial, Helvetica, sans-serif" size="3" color="#666666"><a href="http://thadood.ath.cx/~fatal" target="_blank">Feed
 Your Complier</a></font></b></p>

