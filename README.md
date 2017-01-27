# MARC-21 to MODS conversion

Code Repository for metadata conversion from MARC-21 to MODS (Metadata Object Description Schema)

For more information, please contact claus.zinn@uni-tuebingen.de

# Website

This web service allows you to convert MARC-21 format to MODS.

It makes use of a stylesheet retrieved from http://www.loc.gov/standards/marcxml/xslt

The conversion from MARC-21 to NOD is currently being served at:

```http://weblicht.sfs.uni-tuebingen.de/converter/Marc2MODS/ ```

A REST interface is also available. See webpage above.

# Status

The software has no official release yet, but won't change much in the future, given the
stylesheet's fixed nature.  The software's design mirrors the one of the Marc2EAD software. The
diff is relatively small (different stylesheet, minor differences in website, and configuration
options).

In the future, we might want to offer a unifying website that offers users the various metadata
conversions they can perform.






