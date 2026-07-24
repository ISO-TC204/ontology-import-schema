# incomeLimit

Optional. Income limit for which the incentive is applicable for.
    
<p>If MonetaryAmount is specified, this should be based on annualized income (e.g. if an incentive is limited to those making <$114,000 annually):</p>
    {
        "@type": "MonetaryAmount",
        "maxValue": 114000,
        "currency": "USD",
    }

Use Text for incentives that are limited based on other criteria, for example if an incentive is only available to recipients making 120% of the median poverty income in their area.

**Domain**: [FinancialIncentive](../classes/FinancialIncentive.md)

**Range**: [MonetaryAmount](../classes/MonetaryAmount.md), [Text](../classes/Text.md)

**IRI**: `http://schema.org/incomeLimit`
