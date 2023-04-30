Download Link: https://assignmentchef.com/product/solved-cs240-introduction-to-computing-iii-mp03-templates
<br>
5/5 - (1 vote)







<strong>Objectives</strong>

&#x25aa; To make use of class and function templates

&#x25aa; To use pointers and dynamic memory management

<strong>Project setup</strong>

Create the project <strong>mp03.&lt;FirstLast&gt;</strong>. Replace FirstLast with your name and do not include the &lt;&gt; brackets. For instance, <strong>mp03.SocratisTornaritis</strong>.

Add the provided files to your project:

main.cpp

Name.hpp, Name.cpp

ArrayList.hpp, ArrayList.cpp

The folder <strong>mp03.Firstlast</strong> containing just the source file(s) and text file(s), is the one that you must zip and upload. Do not upload any IDE specific files.

Refer to the appropriate “how to” tutorial notes available on the course website, for instructions on how to create a project and manage its files.

<strong>Problem description:</strong>

This mp has two parts to it. The first is to rewrite the <em>ArrayList</em> example we did in class and change the array elements to <em>Name</em> elements, rather than <em>Name</em> * elements. The second is to convert the <em>ArrayList</em> class to a template and implement the <strong><em>&lt;&lt;()</em></strong> function as a template.




<table width="624">

 <tbody>

  <tr>

   <td width="624">Original list: [John SmithTobby AppleseedMary Appleseed]First name: John SmithIs John Smith before Tobby Appleseed alphabetically? NoCopy list: [Mary PoppinsTobby AppleseedMary Appleseed]Original list: [John SmithTobby AppleseedMary Appleseed]</td>

  </tr>

 </tbody>

</table>

1 / 2                                                                                                                                      Last updated: September 28, 2016 at 7:05 AM

<strong>Program requirements:</strong>

<ul>

 <li><strong>Complete the implementation of the </strong><strong><em>Name</em> </strong></li>

</ul>

Implement the relational operator methods and <strong><em>&lt;&lt;()</em></strong> function. Refer to class examples.

<ul>

 <li><strong>Update the interface file for the </strong><strong><em>ArrayList</em></strong></li>

</ul>

Update the <em>ArrayList</em>‘s declaration to reflect the new element type, which this time is a <em>Name</em> object, rather than a <em>Name</em> *.

<ul>

 <li><strong>Implement the class inline.</strong></li>

</ul>

An inline implementation means that the class declaration is now also the class definition. Copy the relevant code from the implementation file into the interface file. When finished, it will look very much like a Java class implementation, all in one basically. Refer to class example for details.

<ul>

 <li><strong>Remove the </strong><strong><em>ArrayList</em> implementation file from the project.</strong></li>

</ul>

Since we are using inline methods, remove the .cpp file from the project, else you will run into compilation errors.

<ul>

 <li><strong>Now make the </strong><strong><em>ArrayList</em> class into a template. </strong> Turn the ArrayList into a template.</li>

</ul>

As you write your programs from here on out, documentation will be desirable and an essential part of your code. Add the following section to each of your programs to identify relevant information to anyone reading your code. The sample below is what I used for Main.java, so make the appropriate changes to reflect your current/accurate information. This is just a sample, so feel free to add to it if you want, but do not remove anything.

/*    File: &lt;filename&gt;

<ul>

 <li>Name: &lt;your name&gt;</li>

 <li>Revised: &lt;date authored&gt;</li>

 <li>Course: CS240 – Introduction to Computing III</li>

</ul>

*

<ul>

 <li>Desc: &lt;program description&gt;</li>

</ul>

*/