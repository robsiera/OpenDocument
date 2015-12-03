# OpenFiles
Integrated Image Management in DNN (Dotnetnuke),
Integrated PDF search with Lucene,
Add-on to OpenContent


##Minimal requirements:
 * [Dnn v7.4.2](https://dotnetnuke.codeplex.com/)
 * [OpenContent v2.0](https://opencontent.codeplex.com)

##Features

* Enhance the Dnn Filemanager
 * store extra meta data in the dnn content items
 * define several crop areas for images
* Expose helpers for [OpenContent](http://opencontent.codeplex.com/) templates
 * get imageUrl for a certain ratio
 * get document meta data
 * query documents (+search inside pdfs)

##How to use it

* Install the Module
* Create a Host page + install OpenDocument module on it
* Click on the button "create a scheduled task": every 30 min new pdf files will be indexed
* Goto DNN Filemanager, notice that every file has now some additional meta data fields.
* Goto DNN Filemanager, notice that every image file has a cropper function.

##Example template

* not available yet

##Coming soon ...

[![Build by AppVeyor](https://ci.appveyor.com/api/projects/status/github/sachatrauwaen/OpenDocument?branch=master&svg=true)](https://ci.appveyor.com/project/sachatrauwaen/opendocument/)
https://ci.appveyor.com/project/sachatrauwaen/opendocument
