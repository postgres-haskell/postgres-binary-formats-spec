# A binary format specification of PostgreSQL built-in types

## Numeric
```
smallint - word16
integer  - word32
bigint   - word64
decimal - TODO
numeric - TODO
real - float32
double precision - float64
```
## Monetary

## Character
```
char - word8
text, varchar - text[n]
```
## Binary
```
bytea - bytes[n]
```

## Date/Times
TODO

## Boolean
```
bool - word8(1 for True, 0 for False)
```

## Enum
TODO

## Geometric

## Network Address

## Text Search

## UUID

## XML

## JSON

## Array

## Composite

## Range

## Oid
