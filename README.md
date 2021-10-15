# The Swift on Linux Working Group
## *A Road Map for the Future.*
## Purpose of the Working Group
1 - To provide guidelines for methods and frameworks for the easy installation and distribution of the Swift Coding Language on Linux. This is to include as many of the different Linux distributions and CPU architectures as possible. Where possible this should be the standard installation process as used by other coding languages and applications on that system.  

2 - To provide methods and frameworks for the addition of new Distributions and Architectures.

# Primary Functions
To design frameworks and document methods to enable the following:-
## **1 - Packaging**
Each Linux distribution has its own packaging system used for the easy installation, update and removal of items. The `swift.tar.gz` files will need to be converted to the appropriate installation package for each distribution.
### *Example*
>Ubuntu uses the `aptitude` package manager 
Packages use a `.deb` extension  
Installed with `sudo apt install <filename>.deb`

### *Package Name*
An official name for the Swift package will be required and should be uniform over all platforms.  
NOTE: "swift" can not be used as it already exists in the Debian package lists.
### *Versioning*
....... add here ...........

## **2 - Distribution**
Setup and maintain the appropriate package repositories for each distribution.

## **3 - Promotion**
Promote Swift to new users.
Notify existing users of new features and releases.

## **4 - Bug Reporting**
Provide an easy platform for bug reporting for all levels of users.

# Adding New Distributions and Architectures
In addition to the Primary Functions above it is also important to layout a clear path and criteria for the addition of new Distributions e.g. *Fedora* and / or Architectures e.g. *AArch64* to the official Swift.org releases.  
This could be something like this:-

### *Example* - Adding Ubuntu 16.04 for AArch64
>***Step 1*** - Apply for a `Swift Community CI Server`.  
***Step 2*** - Submit the necessary PR's to allow Swift to build patch free.  
***Step 3*** - Release as a `Developer Preview` for community testing.  
***Step 4*** - Submit additions PR's for bug fixing as necessary.  
***Step 5*** - When all tests are passing and known bugs and issues have been addressed then an official request is made to Swift.org to have the new system added as an official release.  
***Step 6*** - Add an official `Swift CI server` for the new system.  
***Step 7*** - Add new system to the official Swift.org releases.
