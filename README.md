# kumar

Does UTF-8 have a BOM?

The UTF-8 BOM is a sequence of bytes at the start of a text stream ( 0xEF, 0xBB, 0xBF ) that allows the reader to more reliably guess a file as being encoded in UTF-8. Normally, the BOM is used to signal the endianness of an encoding, but since endianness is irrelevant to UTF-8, the BOM is unnecessary.

What is BOM code in UTF-16?

U+FEFF

Unicode in the 16-bit UTF-16 form has no prescribed endian orientation for interchange. This requires communication processes to evaluate the endian orientation correctly. To aid in this, the character U+FEFF ZERO WIDTH NO-BREAK SPACE can be used as a Byte Order Mark (BOM).

https://www.ibm.com/docs/en/psfa/7.2.1?topic=formats-byte-order-mark

