# exceptDate

Defines a [[Date]] or [[DateTime]] during which a scheduled [[Event]] will not take place. The property allows exceptions to
      a [[Schedule]] to be specified. If an exception is specified as a [[DateTime]] then only the event that would have started at that specific date and time
      should be excluded from the schedule. If an exception is specified as a [[Date]] then any event that is scheduled for that 24 hour period should be
      excluded from the schedule. This allows a whole day to be excluded from the schedule without having to itemise every scheduled event.

**Domain**: [Schedule](../classes/Schedule.md)

**Range**: [Date](../classes/Date.md), [DateTime](../classes/DateTime.md)

**IRI**: `http://schema.org/exceptDate`
