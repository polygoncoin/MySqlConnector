---
title: MySqlDateTime
---

# MySqlDateTime structure

Represents a MySQL date/time value. This type can be used to store `DATETIME` values such as `0000-00-00` that can be stored in MySQL (when [`AllowZeroDateTime`](../MySqlConnectionStringBuilder/AllowZeroDateTime/) is true) but can't be stored in a DateTime value.

```csharp
public struct MySqlDateTime : IComparable, IConvertible
```

## Public Members

| name | description |
| --- | --- |
| [MySqlDateTime](../MySqlDateTime/MySqlDateTime/)(…) | Initializes a new instance of [`MySqlDateTime`](../MySqlDateTimeType/). (3 constructors) |
| [Day](../MySqlDateTime/Day/) { get; set; } | Gets or sets the day of the month. |
| [Hour](../MySqlDateTime/Hour/) { get; set; } | Gets or sets the hour. |
| [IsValidDateTime](../MySqlDateTime/IsValidDateTime/) { get; } | Returns `true` if this value is a valid DateTime. |
| [Microsecond](../MySqlDateTime/Microsecond/) { get; set; } | Gets or sets the microseconds. |
| [Millisecond](../MySqlDateTime/Millisecond/) { get; set; } | Gets or sets the milliseconds. |
| [Minute](../MySqlDateTime/Minute/) { get; set; } | Gets or sets the minute. |
| [Month](../MySqlDateTime/Month/) { get; set; } | Gets or sets the month. |
| [Second](../MySqlDateTime/Second/) { get; set; } | Gets or sets the second. |
| [Year](../MySqlDateTime/Year/) { get; set; } | Gets or sets the year. |
| [GetDateTime](../MySqlDateTime/GetDateTime/)() | Returns a DateTime value (if [`IsValidDateTime`](../MySqlDateTime/IsValidDateTime/) is `true`), or throws a [`MySqlConversionException`](../MySqlConversionExceptionType/). |
| override [ToString](../MySqlDateTime/ToString/)() | Converts this object to a String. |
| [explicit operator](../MySqlDateTime/op_Explicit/) | Converts this object to a DateTime. |

## See Also

* namespace [MySqlConnector](../../MySqlConnectorNamespace/)
* assembly [MySqlConnector](../../MySqlConnectorAssembly/)

<!-- DO NOT EDIT: generated by xmldocmd for MySqlConnector.dll -->
