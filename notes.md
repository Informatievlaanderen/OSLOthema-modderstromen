# Notes

We follow the idea of SSN/SOSA and thus reuse a lot of their classes and properties.
Therefore, we will only discuss here the other classes and properties.

## Eenheid

This is qudt:Unit which we need for Kwantitatieve Waarde.

## Erosiebestrijdingsmaatregel

No existing class found, thus we created a new one.

## Erosiebestrijdingsmaatregelonderdeel

No existing class found, thus we created a new one.

## Erosiepoel

No existing class found, thus we created a new one.

## Graszone

No existing class found, thus we created a new one.
This one was added mostly to illustrate the fact that our data model supports other Erosiebestrijdingsmaatregelen
besides Erosiepoel.

## Hoeveelheid

This is qudt:Quantity which we use in this track to express the dimensions of an Erosiepoel.

## Hoeveelheidtype

This is similar to SSN/SOSA ObservedProperty but in QUDT.
We need this because we use qudt:Quantity.
In practice, I think this class and ObservedProperty are actually the same.

## Kwantitatieve Waarde

This is qudt:QuantityValue which we use in combination with qudt:Quantity for the dimensions of an Erosiepoel.
It can also be used a result of an Observatie.
This is also mentioned in the 
[alignment between SSN/SOA and QUDT](https://www.w3.org/TR/vocab-ssn/#quantity-values-and-unit-of-measures).

## Numeriek Unie

This is the "class" for all numerical XSD datatypes.
We need it for Kwantitatieve Waarde to say that the value there is a number.

## Onderhoud

We didn't find an existing class for maintenance, so we created a new one.

## Zone

There are zones in other OSLO APs and VOCs,
but they all have different scopes/definitions.
Thus, we create a new one.
