# priceType

Defines the type of a price specified for an offered product, for example a list price, a (temporary) sale price or a manufacturer suggested retail price. If multiple prices are specified for an offer the [[priceType]] property can be used to identify the type of each such specified price. The value of priceType can be specified as a value from enumeration PriceTypeEnumeration or, a UN/EDIFACT 5387 code, or as a free form text string for price types that are not already predefined in PriceTypeEnumeration.

**Domain**: [CompoundPriceSpecification](../classes/CompoundPriceSpecification.md), [UnitPriceSpecification](../classes/UnitPriceSpecification.md)

**Range**: [PriceTypeEnumeration](../classes/PriceTypeEnumeration.md), [Text](../classes/Text.md)

**IRI**: `http://schema.org/priceType`
