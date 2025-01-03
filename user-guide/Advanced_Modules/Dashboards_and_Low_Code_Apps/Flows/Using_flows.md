---
uid: Using_flows
---

# Flows

Flows allow you to modify the behavior of one or more data objects <!--(or variables) TODO: add once variables are available--> in a dashboard or low-code app by applying a series of operators. Similar to the way [GQI queries](xref:About_GQI) are configured, operators are chained together and applied to the data object step by step until a final value is reached, which is then passed to all consumers.

Flows are available starting from DataMiner web 10.4.12. The minimum required server version is 10.4.0 or 10.3.9.<!-- RN 40974 -->

## Data sources

Flows always start from at least one existing data source. The following data sources can be used to initiate a flow:

- **Feeds**: Live or static data inputs, such as text inputs or other widgets providing data.
- **Other flows**: Flows can be chained, with the output of one flow being used as the input for another.
<!--(Variables) TODO: add once variables are available-->

## Operators

To manipulate the data sources in a flow, you can use various operators. For an overview, see [Flow operators](xref:Flow_operators).
