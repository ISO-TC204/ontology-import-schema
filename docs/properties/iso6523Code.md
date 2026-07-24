# iso6523Code

An organization identifier as defined in [ISO 6523(-1)](https://en.wikipedia.org/wiki/ISO/IEC_6523). The identifier should be in the `XXXX:YYYYYY:ZZZ` or `XXXX:YYYYYY`format. Where `XXXX` is a 4 digit _ICD_ (International Code Designator), `YYYYYY` is an _OID_ (Organization Identifier) with all formatting characters (dots, dashes, spaces) removed with a maximal length of 35 characters, and `ZZZ` is an optional OPI (Organization Part Identifier) with a maximum length of 35 characters. The various components (ICD, OID, OPI) are joined with a colon character (ASCII `0x3a`). Note that many existing organization identifiers defined as attributes like [leiCode](http://schema.org/leiCode) (`0199`), [duns](http://schema.org/duns) (`0060`) or [GLN](http://schema.org/globalLocationNumber) (`0088`) can be expressed using ISO-6523. If possible, ISO-6523 codes should be preferred to populating [vatID](http://schema.org/vatID) or [taxID](http://schema.org/taxID), as ISO identifiers are less ambiguous.

**Domain**: [Organization](../classes/Organization.md)

**Range**: [Text](../classes/Text.md)

**IRI**: `http://schema.org/iso6523Code`
