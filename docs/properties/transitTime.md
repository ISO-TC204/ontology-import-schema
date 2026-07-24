# transitTime

The typical delay the order has been sent for delivery and the goods reach the final customer.

  In the context of [[ShippingDeliveryTime]], use the [[QuantitativeValue]]. Typical properties: minValue, maxValue, unitCode (d for DAY).

  In the context of [[ShippingConditions]], use the [[ServicePeriod]]. It has a duration (as a [[QuantitativeValue]]) and also business days and a cut-off time.


**Domain**: [ShippingConditions](../classes/ShippingConditions.md), [ShippingDeliveryTime](../classes/ShippingDeliveryTime.md)

**Range**: [QuantitativeValue](../classes/QuantitativeValue.md), [ServicePeriod](../classes/ServicePeriod.md)

**IRI**: `http://schema.org/transitTime`
