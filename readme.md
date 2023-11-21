  
<span style="font-family:Arial sans-serif;font-size:16px;">WD HTML Export</span>

  
<span style="font-family:Arial sans-serif;font-size:14px;">This example explains how to export data in HTML format with the WLanguage functions.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">The following topics are presented in this example:</span>

<span style="font-family:Arial sans-serif;font-size:14px;">1/ the functions for managing the external files for generating the HTML file</span>

<span style="font-family:Arial sans-serif;font-size:14px;">2/ the operations performed on the HTML tags</span>

<span style="font-family:Arial sans-serif;font-size:14px;">3/ the generation of an HTML report</span>

<span style="font-family:Arial sans-serif;font-size:14px;">The generation of an HTML page is performed from the data found in a memory table.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">By programming</span>

<span style="font-family:Arial sans-serif;font-size:14px;">The principle consists in generating a text file with a "HTM" extension. The WLanguage function named "fWrite" will be used.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">This example easily writes the text strings by respecting the syntax of the HTML language.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">Automatically</span>

<span style="font-family:Arial sans-serif;font-size:14px;">The principle consists in creating a report on table based on the memory table that was previously filled.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">The printout is requested with an HTML output.</span>

  
  
<span style="font-family:Arial sans-serif;font-size:14px;">( \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ° \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ )</span>

  
<span style="text-decoration:underline;font-family:Arial sans-serif;font-size:10px;">Conditions of Use.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">This program is supplied for training purposes.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">The use of this program is the responsibility of the user. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">PC SOFT will not be liable for damage or loss of any nature whatsoever, including data loss, corruption or deterioration as a result of using this program.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Any person owning a WINDEV 28 US license is authorized to use and/or modify the program and to use it in their own applications. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">In this case all references to PC SOFT and/or to WinDev or WebDev must be removed.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">You may not distribute or sell this example program without substantial modification or include it in another application unless the application is very large.</span>

  
<span style="font-family:Arial sans-serif;font-size:10px;">No Hot Line Support is available for this program.</span>

  
<span style="font-family:Arial sans-serif;font-size:10px;">CAUTION: Many users may have modified this program. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">Make sure that you are working with the original version of this program.</span>

  
  
  
  