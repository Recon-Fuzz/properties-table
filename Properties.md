## Format
- creating a separate table for properties in each contract can help keep things clean and easier to track
- property name: use `property_` prefix with a descriptive name of the property definition. If it's a stateful test implemented in a handler just add the name of the handler where it's defined
- description: what the property checks for, in English
- implemented: use ✅ to signify completed, 🚧 for in progress and leave blank if not implemented
- tested: use the ✅ to signify passing, ❌ for failed properties

## Notes
Having descriptive names in the function name shoul allow more easily finding a given property definition without having to look it up in the table.

## <ContractName>
| Property | Description | Implemented | Tested |
| --- | --- | --- | --- |
| `property_x` | <property description in plain English> | ✅/🚧 | ✅/❌ |