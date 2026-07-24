# isUnlabelledFallback

This can be marked 'true' to indicate that some published [[DeliveryTimeSettings]] or [[ShippingRateSettings]] are intended to apply to all [[OfferShippingDetails]] published by the same merchant, when referenced by a [[shippingSettingsLink]] in those settings. It is not meaningful to use a 'true' value for this property alongside a transitTimeLabel (for [[DeliveryTimeSettings]]) or shippingLabel (for [[ShippingRateSettings]]), since this property is for use with unlabelled settings.

**Domain**: [ShippingRateSettings](../classes/ShippingRateSettings.md)

**Range**: [Boolean](../classes/Boolean.md)

**IRI**: `http://schema.org/isUnlabelledFallback`
