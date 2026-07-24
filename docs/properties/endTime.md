# endTime

The endTime of something. For a reserved event or service (e.g. FoodEstablishmentReservation), the time that it is expected to end. For actions that span a period of time, when the action was performed. E.g. John wrote a book from January to *December*. For media, including audio and video, it's the time offset of the end of a clip within a larger file.\n\nNote that Event uses startDate/endDate instead of startTime/endTime, even when describing dates with times. This situation may be clarified in future revisions.

**Domain**: [Action](../classes/Action.md), [FoodEstablishmentReservation](../classes/FoodEstablishmentReservation.md), [InteractionCounter](../classes/InteractionCounter.md), [MediaObject](../classes/MediaObject.md), [Schedule](../classes/Schedule.md)

**Range**: [DateTime](../classes/DateTime.md), [Time](../classes/Time.md)

**IRI**: `http://schema.org/endTime`
