Record Linkage
=========================================
Problem statement:

The typical structure of a record linkage problem can be outlined as follows: We possess an extensive collection of records originating from one or more source systems. It is highly probable that multiple records pertain to the same fundamental entity, whether it be a customer, a patient, or a business or event location. Each entity is associated with various attributes, such as a name, an address, or a birthday, and our task is to utilize these attributes to identify records that correspond to the same entity. Regrettably, the attribute values are not flawless; they may exhibit distinct formatting, contain typos, or have missing information. Consequently, a simple equality test applied to attribute values would result in a substantial number of duplicate records going undetected.

| Name | Address | City | State | Phone |
| ------------- | ------------- |------------- | ------------- |------------- |
| Josh’s Coffee Shop | 1234 Sunset Boulevard | West Hollywood | CA | (213)-555-1212 |
| Josh’s Coffee | 1234 Sunset Blvd West  | Hollywood | CA | (213)-555-1212 |
| Coffee Chain Regional Office | 1400 Sunset Blvd Suite 2 | Hollywood | California | 206-555-1212 |

The first two entries in this table refer to the same small coffee shop whereas the last one is referring to a
different business locations of the same chain of coffee shops
