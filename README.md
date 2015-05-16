libmatthew-java
---------------

These are a selection of libraries for Java which I have written because they
are useful and not provided with normal Java. They are available for download
here and are licensed under the GPL or LGPL. They all come with example
applications using the libraries. 

The ones I consider distribution-worthy are packaged up together. Several other
classes are available separately below. 

##### Unix Sockets Library

This is a collection of classes and native code to allow you to read and write
Unix sockets in Java. 

##### Debug Library

This is a comprehensive logging and debugging solution. 

##### CGI Library

This is a collection of classes and native code to allow you to write CGI
applications in Java. 

##### I/O Library

This provides a few much needed extensions to the Java I/O subsystem. Firstly,
there is a class which will connect and InputStream with an OutputStream and
copy data between them. 

Secondly there are two classes for inserting into an Input or OutputStream pipe
a command line command, so that everything is piped through that command. 

Thirdly there are a pair of classes for splitting streams in two. This can
either be to two OuputStreams, or to an OutputStream and a file. Equivelent to
the UNIX tool tee in UNIX pipes. 

##### Hexdump

This class formats byte-arrays in hex and ascii for display.


### Usage

    # build
    make
    
    # installation
    sudo make install
    
    # uninstallation
    sudo make uninstall

### Library related...
 - [libmatthew-0.8-x86-sources.jar](http://www.java2s.com/Code/JarDownload/libmatthew/libmatthew-0.8-x86-sources.jar.zip) ([jar info](http://www.java2s.com/Code/Jar/l/Downloadlibmatthew08x86sourcesjar.htm)) - the repository was created based on this jar. 


 - [libmatthew-java-0.8.jar](http://www.java2s.com/Code/JarDownload/libmatthew/libmatthew-java-0.8.jar.zip) ([jar info](http://www.java2s.com/Code/Jar/l/Downloadlibmatthewjava08jar.htm)) - compiled library in single jar.

 - [mavenized repo](https://bitbucket.org/rynkowsg/libmatthew-java)
