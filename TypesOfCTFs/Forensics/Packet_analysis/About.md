# Packet Analysis
Network (packet capture) forensics is more about metadata analysis than content analysis, as most network sessions are TLS-encrypted between endpoints now.
You will be given a pcap file {packet capture dump}, and you’ll try to decode, analyze, and interpret it, using tools such as Wireshark.
Questions can be asked on anything(to locate flag that is) - the browser used , the password/username if the user sends it in plaintext or whatever encryption
or listening to a VOIP call without encryption.

## Important
A note about PCAP vs PCAPNG: there are two versions of the PCAP file format; PCAPNG is newer and not supported by all tools. You may need to convert a file from PCAPNG to PCAP using Wireshark or another compatible tool, in order to work with it in some other tools.

> Refer [Tools](Tools/tools.md)

> Refer [Tips](tips.md)
