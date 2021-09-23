# Panoply

* Panoply plots geo-referenced and other arrays from netCDF, HDF, GRIB, and other datasets.

* Panoply is a cross-platform application that runs on Macintosh, Windows, Linux and other desktop computers.

* With Panoply 4 you can:

> Slice and plot geo-referenced latitude-longitude, latitude-vertical, longitude-vertical, time-latitude or time-vertical arrays from larger multidimensional variables.
> Slice and plot "generic" 2D arrays from larger multidimensional variables.

> Slice 1D arrays from larger multidimensional variables and create line plots.

> Combine two geo-referenced arrays in one plot by differencing, summing or averaging.

> Plot lon-lat data on a global or regional map using any of over 100 map projections or make a zonal average line plot.

> Overlay continent outlines or masks on lon-lat map plots.

> Use any of numerous color tables for the scale colorbar, or apply your own custom ACT, CPT, or RGB color table.

> Save plots to disk GIF, JPEG, PNG or TIFF bitmap images or as PDF or PostScript graphics files.

> Export lon-lat map plots in KMZ format.

> Export animations as MP4 video or as a collection of invididual frame images.

> Explore remote THREDDS and OpenDAP catalogs and open datasets served from them.

 * Get PANOPLY at : https://www.giss.nasa.gov/tools/panoply/download/PanoplyJ-4.12.11.zip   for Linux
 
 ### For installing Panoply we requires JAVA Runtime Environment and JAVA Development Kit. 
 
 # INSTALLATION OF JAVA in Ubuntu
 
 To install JAVA Runtime Environment(JRE):
    
    $ sudo apt install default-jre
    
The JRE will allow you to run almost all Java software.

We may need the Java Development Kit (JDK) in addition to the JRE in order to compile and run some Panoply, because simply installing JRE is unable to open Panoply. To install the JDK, execute the following command, which will also install the JRE:

    $ sudo apt install default-jdk
    
Now update the ubuntu using $ sudo apt-get update

# INSTALLATION OF PANOPLY

After you install zip file from the link above, unzip it using command:
   
    $ unzip PanoplyJ-4.12.11.zip

We will get a directory named /jars with all the scripts , a shell script , and a README file 
>jars/  
>panoply_macos.sh  
>panoply.sh  
>README.txt
 
Till now the shell script panoply.sh is not executable so we need to make it executable. It has only read and write permissions. So, we need to provide the executable permission.

    $ chmod +x panoply.sh
   
Now, this will become executable.We can now run the script as:

    $ ./panoply.sh
    
If nothing happens or says permission denied, then don't worry. Navigate to the folder /jars where all the scripts are placed and run the jar file Panoply.jar using following command:

    $ java -jar Panoply.jar
    
    
A pop up GUI window will appear.

Congrats! 

Now you are ready to use Panoply.
