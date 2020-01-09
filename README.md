# thinRAD ( NYA<sup>1</sup> edition )
a tool to speed up user interface coding in [thinBasic](https://www.thinbasic.com)

## Setup 
Setup is almost the same as for [thinternational](https://github.com/DirectuX/thinternational/blob/master/README.md "Setup")

Note: append the following section to _thinAir_Tools.ini_

<pre>
[thinRAD]
Menu=thinRAD
CommandLine=%thinbasicinstallpath%\thinbasicc.exe "%thinAirinstallpath%\Tools\thinRAD\thinRAD.tbasic " %sourcecodefullpathnameext%
SaveScriptBefore=true
</pre>


<sup>1</sup> Not Yet Alpha

## Usage

in your script
write an empty "UI" region / end region

thinRAD will find all #Resource files and fill the "UI" region with callback functions. 

## Demo

Run the script with full-path-to-DemoRAD.tbasic as command line parameter or via the user tool menu after setup.
RAD.rc must be in the same directory than DemoRAD.tbasic

## Roadmap

complete controls recognition

'update' mode
