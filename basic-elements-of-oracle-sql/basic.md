# BASIC ELEMENTS OF ORACLE SQL.

## DATA TYPES.

Oracle Database provides a number of built-in data types as well as several categories for user-defined types that can be used as data types. The syntax of Oracle data types appears in the diagrams that follow. The text of this section is divided into the following sections.



We have some categories for for datatypes.

- Scalar Type: Contains an atomic value.
- Non Scalar Type (Also called collection): Contains a  set of values.
- Large Object (LOB): Representing  a large scalar value of binary or character.



## ORACLE BUILT-IN DATA TYPES.


## LARGE OBJECTS 

It is a data type that is used to store variable-length binary or characer data.LOBS are designed to handle large amounts of data, such as text documents, images, audios, and video files which may not fit comfortably in a standard relational database row.

There are three main types of LOBS in Oracle.

1. **CLOB(Character Large Object)**: This type is used for storing large amounts of character data, such as text document. It can store up to 4 Gigabytes of character data.

2. **BLOB(Binary Large Object)**: BLOB is used for storing  binary data, such  as images or multimedia files. It can store  up to 4 gigabytes of binary data.

3. **NCLOB(National Character Large Object)**: Similar to CLOB,but used for storing large amounts of national character set data. It can store up to 4 Gigabytes.



