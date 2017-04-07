ASSIGNMENT SAAD ULLAH - CS131040
 Advantages of XML:
• It is a simultaneously human- and machine-readable format.
• XML is heavily used as a format for document storage and processing, both online and offline. • It is platform-independent, thus relatively immune to changes in technology.
• It is based on international standards.
Disadvantages of XML:
• XML namespaces are problematic to use and namespace support can be difficult to correctly implement in an XML parser.
• XML syntax is redundant or large relative to binary representations of similar data.
• XML is commonly depicted as “self-documenting” but this depiction ignores critical ambiguities.
Advantages of Annotations:
• Static type checking - the compiler will check for you where the annotation (once defined properly) is applicable.
• Clean code - it's much easier to see (visually) the meta data defined in annotations. 
• Because annotations are Java code, there is no need to "switch" between writing Java and XML.
• Using the IDE's "find references" feature, you can quickly see if the project is using a particular configuration attribute. 
Disadvantages of Annotation: 
Disadvantage of the annotation is that you need to recompile the code if you do a little change in it.









ASSIGNMENT SAAD ULLAH - CS131040
HTTP vs. HTTPS
In the beginning, network administrators had to figure out how to share the information they put out on the Internet.
They agreed on a procedure for exchanging information and called it HTTP. HTTP stands for hypertext transfer protocol. It’s a protocol that allows communication between different systems. Most commonly, it is used for transferring data from a web server to a browser to view web pages.
Once everyone knew how to exchange information, intercepting on the Internet was not difficult. So knowledgeable administrators agreed upon a procedure to protect the information they exchanged. The protection relies on SSL Certificate to encrypt the online data. Encryption means that the sender and recipient agree upon a "code" and translate their documents into random-looking character strings.
The procedure for encrypting information and then exchanging it is called Hyper Text Transfer Protocol Secure (HTTPS).
With HTTPS if anyone in between the sender and the recipient could open the message, they still could not understand it. Only the sender and the recipient, who know the "code," can decipher the message.
Humans could encode their own documents, but computers do it faster and more efficiently. To do this, the computer at each end uses a document called an "SSL Certificate" containing character strings that are the keys to their secret "codes". SSL certificates contain the computer owner's "public key."









ASSIGNMENT SAAD ULLAH - CS131040
Sequence vs. Auto-Increment
In Oracle, you can create an auto number field by using sequences. A sequence is an object in Oracle that is used to generate a number sequence. This can be useful when you need to create a unique number to act as a primary key.
MySQL uses the AUTO_INCREMENT keyword to perform an auto-increment feature. By default, the starting value for AUTO_INCREMENT is 1, and it will increment by 1 for each new record.
* Auto increment is tied to a column in a single table, only one per table. Oracle sequence is not.
* A nice feature about auto increment is that you are guaranteed that it will never fail.
* On database restart, auto increment is reset to highest column value. Oracle sequence is not.

