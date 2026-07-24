# value

The value of a [[QuantitativeValue]] (including [[Observation]]) or property value node.\n\n* For [[QuantitativeValue]] and [[MonetaryAmount]], the recommended type for values is 'Number'.\n* For [[PropertyValue]], it can be 'Text', 'Number', 'Boolean', or 'StructuredValue'.\n* Use values from 0123456789 (Unicode 'DIGIT ZERO' (U+0030) to 'DIGIT NINE' (U+0039)) rather than superficially similar Unicode symbols.\n* Use '.' (Unicode 'FULL STOP' (U+002E)) rather than ',' to indicate a decimal point. Avoid using these symbols as a readability separator.

**Domain**: [MonetaryAmount](../classes/MonetaryAmount.md), [PropertyValue](../classes/PropertyValue.md), [QuantitativeValue](../classes/QuantitativeValue.md)

**Range**: [Boolean](../classes/Boolean.md), [Number](../classes/Number.md), [StructuredValue](../classes/StructuredValue.md), [Text](../classes/Text.md)

**IRI**: `http://schema.org/value`
