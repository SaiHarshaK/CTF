# Forensic
Un-delete the file containing flag or file with some unknown file extension.

zip files do not encrypt the filenames and original file sizes of the compressed files they contain.
{zip -F input.zip --out output.zip} and {zip -FF input.zip --out output.zip} attempt to repair a corrupted zip file.

The file header of PDF can have a range of headers so yup, PDF files can be some other file.

For Audio & Videdo analysis, Your first step must always be to check the file with exiftool(mentioned in tools) for its metadata and content type.
Also, check least-significant-bits (LSB) for a secret message.

## Majority Based on...

    Archive files (ZIP, TGZ)
    Image file formats (JPG, GIF, BMP, PNG)
    Filesystem images (especially EXT4)
    Packet captures (PCAP, PCAPNG)
    Memory dumps
    PDF
    Video (especially MP4) or Audio (especially WAV, MP3)
    Microsoft's Office formats (RTF, OLE, OOXML)


## PDF Analysis Hiding places:
    non-visible layers
    Adobe's metadata format "XMP"
    the "incremental generation" feature of PDF wherein a previous version is retained but not visible to the user
    white text on a white background
    text behind images
    an image behind an overlapping image
    non-displayed comments


