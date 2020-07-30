---
title: Working with MapiNote in PST
type: docs
weight: 80
url: /net/working-with-mapinote-in-pst/
---


## **Adding MapiNote to PST**
[Create a New PST File and Add Subfolders](/net/create-new-pst-file-and-add-subfolders/#creating-a-new-pst-file-and-add-subfolders) showed how to create a PST file and add a subfolder to it. With Aspose.Email you can add a [MapiNote](https://apireference.aspose.com/net/email/aspose.email.mapi/mapinote) to the Notes subfolder of a PST file that you have created or loaded. To add a [MapiNote](https://apireference.aspose.com/net/email/aspose.email.mapi/mapinote) to a PST:

1. Create a template [MapiNote](https://apireference.aspose.com/net/email/aspose.email.mapi/mapinote) using Microsoft Outlook and save it as an MSG file.
1. Load the saved MSG note into a [MapiMessage](https://apireference.aspose.com/net/email/aspose.email.mapi/mapimessage) object.
1. Create a [MapiNote](https://apireference.aspose.com/net/email/aspose.email.mapi/mapinote) object and load the template MSG note.
1. Set the [MapiNote properties](https://apireference.aspose.com/net/email/aspose.email.mapi/mapinote/properties/index).
1. Create a PST using the [PersonalStorage.Create()](https://apireference.aspose.com/net/email/aspose.email.storage.pst/personalstorage/methods/create/index) method.
1. Create a pre-defined folder (Notes) at the root of the PST file by accessing the root folder and then calling the [AddMapiMessageItem()](https://apireference.aspose.com/net/email/aspose.email.storage.pst/folderinfo/methods/addmapimessageitem) method.

The following code snippet shows you how to create a [MapiNote](https://apireference.aspose.com/net/email/aspose.email.mapi/mapinote) and then add it to the notes folder of a newly created PST file.



{{< gist "aspose-com-gists" "6e5185a63aec6fd70d83098e82b06a32" "Examples-CSharp-Outlook-AddMapiNoteToPST-AddMapiNoteToPST.cs" >}}
