Download Link: https://assignmentchef.com/product/solved-ece380-lab-01-quartus-prime-tutorial
<br>



In this lab, students get familiar with VHDL, a hardware description language, and Quartus Prime, CAD software. Students will go through three design methods in the CAD software, Quartus, by following a provided tutorial in this lab.

Quartus Prime contains powerful tools for hardware design and implementation. When progressing through the curriculum, the students will use VHDL and Quartus often. So, this is prerequisite material that students are expected to master.

<h1>Lab procedures</h1>

<strong>Step 1: Learn via Quartus Prime Tutorial </strong>

Please read <em>Tutorial 1 —Using Quartus II CAD Software </em>(in lab01_quartus_tutorial.pdf). This tutorial from the textbook deals with Quartus II (v 7.0).




<strong>Important: You will use Quartus Prime (v 16.0) throughout this semester. Therefore, you need to follow an updated guide, lab1_tutorial_guide.pdf for the interface operation in Quartus Prime (v 16.0). </strong>




<em>Introduction to Simulation of VHDL Designs</em> (supplement_quartusii_simulation_vhdl.pdf, in the same folder with this document) will also be helpful.




The major differences are listed as below:

<ul>

 <li><strong>Family and Device Settings. </strong>You can choose <em>Cyclone V(E/GX/GT/SX/SE/ST)</em> when creating a new project. From the list of available devices, choose the device called <em>5CSEMA5F31C6</em>.</li>

 <li><strong>Using the Compiler.</strong> Click <em>Processing&gt; Start Compilation</em> (There is also a toolbar icon for this command, which looks like a purple triangle), instead of <em>Processing &gt;Compiler Tool</em> or <em>Processing &gt; Start &gt; Start Analysis &amp; Synthesis</em>.</li>

 <li><strong>Using the Waveform Editor.</strong> Click <em>File&gt;New&gt;University Program VWF </em>(If you do not see this option, <strong>University Program</strong> needs to be installed), instead of File&gt; <em>New &gt;Other files&gt;Vector Waveform File</em>.</li>

 <li><strong>Performing the Simulation. </strong>Click <em>Simulation&gt;Run Functional Simulation</em> instead of the two steps: <em>Assignments &gt; Settings</em> and <em>Processing &gt; Generate Functional Simulation Netlist</em>.</li>

</ul>




Before your lab session with the TA, you need to read <em>Tutorial 1 – Using Quartus II CAD Software</em> carefully and go through the tutorial procedures B.1 to B.5.




<strong>Step 2: Generate VHDL results: </strong>

During your lab session, please demonstrate the procedures of the following three design examples in lab01_quartus_tutorial.pdf to the TA:

<ul>

 <li>3 Design Entry Using Schematic Capture (tutorial1designstyle1)</li>

 <li>4 Design Entry Using VHDL (tutorial1designstyle2)</li>

 <li>5.1 Using Schematic Entry at the Top Level (tutorial1designstyle3)</li>

</ul>

<strong> </strong>

Some advice for successful compilation and simulations:

<ul>

 <li>To start a new design, you should create a new project rather than a new file.</li>

 <li>You need to copy the VHDL codes in their exact forms.</li>

 <li>Entity in your highest level VHDL code should match with your project entity name.</li>

</ul>

<strong> </strong>

<strong>Note: you need to get TA’s signature after your successful demo. </strong>

<strong> </strong>

<strong>Step 3: Lab Report </strong>

Please assemble all of the above results into a lab report. A sample report format is attached (supplement_sample_lab_report.pdf). Please submit the report to the TA in the beginning of next lab session (Lab 2).




<strong>Include the following items in your lab report: </strong>

<ul>

 <li>Tutorial1designstyle1: Block   design file       (*.bdf)             of         the       schematic (example_schematic.bdf)</li>

 <li>Tutorial1designstyle1: Simulation vector waveform file (.vwf) after the functional simulation of the schematic (example_schematic.vwf)</li>

 <li>Tutorial1designstyle2: VHDL source file (*.vhd) (example_vhdl.vhd)</li>

 <li>Tutorial1designstyle2: Simulation vector waveform file (.vwf) after the functional simulation of the VHDL source code (example_vhdl.vwf)</li>

 <li>Tutorial1designstyle3: VHDL source file (.vhd) (vhdlfunctions.vhd)</li>

 <li>Tutorial1designstyle3: Block   design file       (*.bdf)             of         the       schematic (example_mixed1.bdf)</li>

 <li>Tutorial1designstyle3: Simulation vector waveform file (.vwf) after the functional simulation of the mixed schematic (example_mixed1.vwf)</li>

 <li>Tutorial1designstyle3: Block symbol file, vhdlfunctions.bsf, generated by Quartus for the sub-circuit represented by vhdlfunctions.vhd</li>

</ul>







<strong>Grades</strong> for Lab #1 will be determined according to the following:




Demo (with TA’s signature): 50 pts

Report: 50 pts

Total points for Lab #1 = 100 points




Note: The report should at least include the following items:

<ul>

 <li>(4 pts) example_schematic.bdf</li>

 <li>(4 pts) example_schematic.vwf</li>

 <li>(4 pts) example_vhdl.vhd</li>

 <li>(4 pts) example_vhdl.vwf</li>

 <li>(3 pts) vhdlfunctions.vhd</li>

 <li>(4 pts) example_mixed1.bdf</li>

 <li>(4 pts) example_mixed1.vwf</li>

 <li>(3 pts) vhdlfunctions.bsf</li>

</ul>

<strong> </strong>

<strong> </strong>

<h1>Bonus 25 points: Installation of Quartus Prime</h1>

<strong> </strong>

Please download and install “Quartus Prime Lite Edition” through: <a href="http://dl.altera.com/?edition=web">http://dl.altera.com/?edition=web</a>




Select “<em>Release: 16.0</em>”, and “<em>Combined Files</em>“. This is the same version as the one in the lab. The CD in your textbook is outdated. Please do not use it.




Decompress the downloaded file and install Quartus Prime. You can use free software 7zip, http://www.7-zip.org/, to decompress the file.




Note that Quartus Prime only supports 64 bit machines.




If you use Mac laptops, you can create a dual boot, where you can establish a Windows operating system. The other option for Apple users is to install in a virtual machine environment. The latter option is slow, as multiple students reported.




<strong>Bring your laptop to the lab session and show your installation to the TA. You will get extra 25 points. Each member gets his/her own bonus points for the installation.  </strong>




<strong>Additional materials: </strong>

You can also read:

<ul>

 <li><a href="http://www.altera.com/literature/lit-qts.jsp">http://www.altera.com/literature/lit-qts.jsp </a>for Quartus II development software documentation,</li>

 <li><a href="http://esd.cs.ucr.edu/labs/tutorial/">http://esd.cs.ucr.edu/labs/tutorial/ </a>for VHDL basics, and</li>

 <li><em>Introduction to         Simulation       of         VHDL Designs</em>,          as         attached supplement_quartusii_simulation_vhdl.pdf.</li>

 <li><em>Quartus II         0   introduction    for       VHDL users</em>,   as         attached supplement_quartusii_v15_intro_vhdl.pdf.</li>

</ul>




<strong> </strong>

<strong> </strong>

<strong> </strong>