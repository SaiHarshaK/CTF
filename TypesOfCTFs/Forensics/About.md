# Digital Forensics
A very broad category.Any challenge to examine and process a hidden piece of information out of static data files (as opposed to executable programs or remote servers) could be considered a Forensics challenge. real-world forensics typically requires that a practictioner find indirect evidence of maliciousness: either the traces of an attacker on a system, or the traces of "insider threat" behavior.network (packet capture) forensics is more about metadata analysis than content analysis, as most network sessions are TLS-encrypted between endpoints now.

## U need...
A scripting Language (i use python)
Knowing how to manipulate binary data (byte-level manipulations) in that language (example, Writing or reading a file in binary mode)
To Recognize formats, protocols, structures, and encodings (example, pcap is used for packet analysis). These are better acquired from practice.

## Filesystems analysis
You may not be looking for a file in the visible filesystem at all, but rather a hidden volume, unallocated space (disk space that is not a part of any partition), a deleted file, or a non-file filesystem structure

## Memory dump analysis
A snapshot of memory often contains context and clues that are impossible to find on disk because they only exist at runtime (operational configurations, remote-exploit shellcode, passwords and encryption keys, etc).We can determine information about running programs, the operating system, and the overall state of a computer. 

## PDF file analysis
To display the structure of a PDF, you can either browse it with a text editor, or open it with a PDF-aware file-format editor like Origami.  
[Refer this](https://github.com/corkami/docs/blob/master/PDF/PDF.md) for PDF file format tricks

## Audio & Video analysis
Audio and video file trickery.

## Office file analysis
Microsoft has created dozens of office document file formats, many of which are popular for the distribution of phishing attacks and malware because of their ability to include macros (VBA scripts).   

There are two generations of Office file format: the OLE formats (file extensions like RTF, DOC, XLS, PPT), and the "Office Open XML" formats (file extensions that include DOCX, XLSX, PPTX). Both formats are structured, compound file binary formats that enable Linked or Embedded content (Objects). OOXML files are actually zip file containers  
(try - unzip file_name.docx in terminal)  
[Refer this](https://github.com/grierforensics/officedissector/blob/master/doc/html/_sources/txt/ANALYZING_OOXML.txt) - For OOXML analysis

Analyzing a VBA macro to determine its behavior.A typical VBA macro in an Office document, on Windows, will download a PowerShell script to %TEMP% and attempt to execute it, in which case you now have a PowerShell script analysis task too.you can set breakpoints and create watch variables and capture values after they have been unpacked but before whatever payload behavior has executed(you can use libre office).  

> Refer [Tools](Tools/tools.md)

> Refer [Tips](tips.md)

> Refer [Packet Analysis](Packet_analysis/About.md)
