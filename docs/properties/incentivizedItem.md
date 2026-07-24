# incentivizedItem

The type or specific product(s) and/or service(s) being incentivized.
<p>DefinedTermSets are used for product and service categories such as the United Nations Standard Products and Services Code:</p>
    {
        "@type": "DefinedTerm",
        "inDefinedTermSet": "https://www.unspsc.org/",
        "termCode": "261315XX",
        "name": "Photovoltaic module"
    }

<p>For a specific product or service, use the Product type:</p>
    {
        "@type": "Product",
        "name": "Kenmore White 17" Microwave",
    }
For multiple different incentivized items, use multiple [[DefinedTerm]] or [[Product]].

**Domain**: [FinancialIncentive](../classes/FinancialIncentive.md)

**Range**: [DefinedTerm](../classes/DefinedTerm.md), [Product](../classes/Product.md)

**IRI**: `http://schema.org/incentivizedItem`
