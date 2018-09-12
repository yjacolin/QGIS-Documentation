.. only:: html

   |updatedisclaimer|

Appendices
===========

.. index:: Data Types

Data Types
-----------


+-----------+---------------------------+--------+------------+---------------------------------+
| Type      | What does it mean?        | Size   | Python2/3  | Range Number                    |
+-----------+---------------------------+--------+------------+---------------------------------+
| Byte      | 8-bit int                 |   8    |            |                                 |
| UInt16    | Unsigned 16-bit int       |   16   | Int        | 0 to 65,535                     |
| Int16     | signed 16-bit int         |   16   | Int        | -32,768 to 32,767               |
| UInt32    | unsigned 32-bit int       |   32   | Int        | 0 to 4,294,967,295              |
| Int32     | signed 32-bit int         |   32   | Int        | -2,147,483,648 to 2,147,483,647 |
| Float32   | 32-bit IEEE float         |   32   | float      | -3.4E38 to 3.4E38               |
| Float64   | 64-bit IEEE float         |   64   | float      | -1.7E308 to 1.7E308             |
| CInt16    | complex 16-bit int        |   16   | Int        | -32,768 to 32,767               |
| CInt32    | complex 32-bit int        |   32   | Int        | -2,147,483,648 to 2,147,483,647 |
| CFloat32  | complex 32-bit IEEE float |   32   | float      | -3.4E38 to 3.4E38               |
| CFloat64  | complex 64-bit IEEE float |   64   | float      | -1.7E308 to 1.7E308             |
+-----------+---------------------------+--------+------------+---------------------------------+

Complex data types in raster are mostly used for SAR (Synthetic-aperture radar
images).

Size matters as it implies bigger files.
