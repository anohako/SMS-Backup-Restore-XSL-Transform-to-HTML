# SMS-Backup-Restore-XSL-Transform-to-HTML
This XSL interprets an XML backup of SMS and MMS messages produced by the Android app SMS Backup &amp; Restore to produce an easily readable HTML webpage. It sorts all messages by date, interleaving SMS and MMS messages that otherwise are separated in the original XML file. Optionally, it can output only messages involving a specified contact.  To use it, place sms.xsl in the same folder as the XML file, then open the XML file in a web browser. Firefox can handle this locally; Chrome can't. 

It is based on the XSL code from https://github.com/devadvance/sms-backup-reader-2/
