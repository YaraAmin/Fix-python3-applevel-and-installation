INSTALLATION
Download python
Install pip by :    copy and paste these content in a file as get-pip.py
                        copy and paste get-pip.py into python folder.C:\Python27  
Double click to get-pip.py file.it will install pip to your computer. 
Repeat the same for setuptool.py
Download protobuf from https://github.com/protocolbuffers/protobuf ,PS: protobuf is not a command you convert your files using step 11
install protoc by:  download protoc-win form:https://github.com/protocolbuffers/protobuf/releases
Add it to your PATH environment variable to be accessible from the calling directory when you're in the CMD  as :”C:\proto3\bin”
At the CMD: pip install protoc 
Download pycharm from :https://www.jetbrains.com/pycharm/download/#section=windows
Build your virtual environment using: pip install virtualenv at the IDE command-terminal-
Install “protobuf support” to convert python files to protofiles
Install all protobuf pacakage from: file -- setting-- project:proto --project interpter --packages
Install google and google-action
Convert your proto files to meta using :protoc -I=filename/ --python_out=filename/ packagename/filename.proto
-------------------------------------------------------------------------------------------
NOTES
Shortcut to run: ctrl+f5 
Shortcut to increase font: ctrl+shift+A
Name your package or any file as “enum” generate an error in enum installation
“Import enum” is your .pb2 file solves the problem of enum installing in CMD or package 
At your .pb2 file in importing line :import  complex_pb2 as complex_pb2 not import  complex_pb2 as complex.pb2 or anything else
Q and clang for Syntax highlighting and Code completion
---------------------------------------------------------------------------------------------
Quickfix installation
Install all quickfix .whl files from here: https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyyaml
Try to install the version fits your python version by trial and error using “pip install path/filename.whl --user”
DOC: http://www.quickfixengine.org/quickfix/doc/html/?quickfix/doc/html

APPLICATION
DataDictionary=C:/Users/Yara/Downloads/quickfix-1.15.1/quickfix-1.15.1/spec/FIX42.xml // put here your fix version of xml/proto path in your quickfix folder

Convert XML file to protobuf
Convert  xml file to json file by using “import xmltodict
import pprint
import json
with open('filename.xml') as fd:
   doc = xmltodict.parse(fd.read())”
Install : pip install --upgrade google-api-python-client
pip install google-cloud 
pip install google-cloud-vision
pip install protobuf
-------------------------------------------------------------------------------------------





