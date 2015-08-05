## Search large files, quickly ##
# [Standalone 1.1 Newest](http://code.google.com/p/forensic-image-search/downloads/detail?name=Release_1.1.zip&can=2&q=) #
[Download Installer 1.0 Old](http://code.google.com/p/forensic-image-search/downloads/detail?name=fisInstaller.msi&can=2&q=)  [Sourcecode](http://code.google.com/p/forensic-image-search/downloads/detail?name=SourceCode.zip&can=2&q=) [Brazilian Portuguese](http://code.google.com/p/forensic-image-search/downloads/detail?name=port_1_1b.zip&can=2&q=#makechanges) thanks to Paulo Guzmán

### Benefits ###
  * Quickly search the whole of that massive file for interesting data
  * Use it to search disk images for delete files and log files
  * Automatically scans for suspicious data that you didn't know you were looking for
  * Zoom in on interesting data and view the surrounding information


### How it works ###
  * Forensic image search takes a single large file, and creates an inverted index. This inverted index can then be searched extremely quickly.

On a typical laptop the indexing process takes about 5 minutes for a 600mb CD sized file. Searches are near instant.

Created by Christopher Doman (http://www.christopherdoman.com) after finding a need for quick forensic analysis of disk images whilst competing in the SOPHOS Linux Forensics Cyber Security Challenge run by James Lyne (https://cybersecuritychallenge.org.uk/sophos-linux-forensics.php)

Screenshots
![http://forensic-image-search.googlecode.com/files/search.png](http://forensic-image-search.googlecode.com/files/search.png)
[Building Index](http://forensic-image-search.googlecode.com/files/buildindex.png) [Suspicious Files](http://forensic-image-search.googlecode.com/files/suspicious.png)

How it works
  * Text is extracted from a file
  * These words are then put into an inverted index, a data structure typically used by search engines for fast search
  * This inverted index is imported into a SQL Lite database for later querying
  * The database is automatically and manually searched for interesting words

The application includes the public domain Sql Lite executable. Also included is the Sys Internals strings utility, by using this application you agree to the Sys Internals EULA.