This zip file contains all the files that you need to start using the JSim
simulator.

Please extract the files within this zip file into a folder, e.g., on your
desktop. (That is, never open the files from within the zip file itself, which
will cause problems and headaches later on!)

The main executable is "jsim.jar". Note that you will need to install the Java
Runtime Environment (JRE) on your computer to run this executable. If you have
the Java SE Development Kit (JDK) installed, then you should already have the
JRE installed. If it is not installed, you can download the JRE installer from:

  https://www.java.com/en/download/

After installing the JRE, simply double-click the jsim.jar file. If that does
not work, try going into the terminal / command prompt of your operating system
then running it using the java command:

  java -jar C:\path\to\jsim.jar

Note that the -jar option is needed.

The other files are as follows:

  lab2.jsim    - open this file in JSim to begin the lab exercise!

  8clocks.jsim - support files that you will need for the lab (do NOT delete!)
  nominal.jsim
  stdcell.jsim

  quickref.pdf - technical quick reference manual (we recommend going through
                 the CSCI 50.02 lecture slides first before you look at this)

Technical note: The support files in this version of JSim has been modified for
the CSCI 50.02 class. Specifically, vdd is changed from 3.3V to 5V, the clock
pulse range is modified to [0, 5], and inverted clocks were added. If you ever
use a version of JSim from another source (e.g., from the original MIT 6.004
class materials), make sure to apply these changes.

Happy hacking! - eric
