############ General info about QT installation ############

qt-opensource-windows-x86-5.14.2                        - Qt 5.14.2 installer
qt-creator-opensource-windows-x86_64-10.0.1             - QtCreator 10.0.1 installer

!!! Important !!!
Disable Internet connection to allow for offline install. Otherwise it will ask for credentials to Qt online account.

Order of installation is up to you, but recommended is:
1. Qt (i.e. 5.14.2). This is called a Kit and it contains compilers, libs and docs. The whole toolchain.
2. Qt Creator (i.e. 10.0.1)

If you have launched Qt Creator for the 1st time, you will need to link it the Qt kit installed on your PC.
Otherwise Qt Creator will just be an IDE without any toolchain to build the code.

When installing Qt kit, you may be asked what compilers and additional tools to install (@see qt-install1.png)
Select the compiler you want (i prefer mingw for 64-bit) and tools you want additionally (i.e. Charts) then install.
All of the essential Qt libs and documentation is always installed.
Also always installed is: old QtCreator (i.e. 4.11.1) and Qt Designer (a tool to graphically design the GUI for the application).
All necessary libs, plugins, examples, even documentation is all included in the offline installation.
Documentation for almost anything is accessed through QtCreator 'Help' section.

Upon running Qt Creator, you can:
 - Use Edit -> Preferences... to set the IDE language and link the Kits. All the configuration stuff for the IDE.
- Kit compromises of GCC, G++ compilers, Cmake and the target device. May be best to select the default Kit with compiler that was installed with Qt. (Qt may offer Kits with compilers that it found on your PC also)
- Under the Welcome section you may open the Examples section that allows you to inspect, build and run example projects.
- Under the Help section you can search for any information you seek (open the Search option to type the keywords)

