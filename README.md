# `TabularData`

This repository contains a WIP open-source implementation of the [`TabularData` framework](https://developer.apple.com/documentation/tabulardata/), usable on Linux.

## Porting Progress

### Data Tables

- [ ] `DataFrame`
- [ ] `DataFrameProtocol`

#### JSON

- [ ] `JSONType`
- [ ] `JSONReadingOptions`
- [ ] `JSONWritingOptions`

#### CSV

- [ ] `CSVType`
- [ ] `CSVReadingOptions`
- [ ] `CSVWritingOptions`

#### Row grouping

- [ ] `RowGrouping`
- [ ] `RowGroupingProtocol`
- [ ] `GroupSummaries`

### Typed Columns

- [ ] `Column`
- [ ] `ColumnSlice`
- [ ] `FilledColumn`
- [ ] `DiscontiguousColumnSlice`
- [ ] `ColumnProtocol`
- [ ] `OptionalColumnProtocol`

### Type-Erased Columns

- [ ] `AnyColumn`
- [ ] `AnyColumnSlice`
- [ ] `AnyColumnProtocol`
- [ ] `AnyColumnPrototype`

### Statistical Summaries

- [ ] `NumericSummary`
- [ ] `CategoricalSummary`
- [ ] `AnyCategoricalSummary`

### Errors

- [ ] `JSONReadingError`
- [ ] `CSVReadingError`
- [ ] `CSVWritingError`
- [ ] `ColumnEncodingError`
- [ ] `ColumnDecodingError`
- [ ] `SFrameReadingError`

### Supporting Types

- [ ] `JoinKind`
- [ ] `Order`
- [ ] `ColumnID`
- [ ] `FormattingOptions`
- [ ] `SummaryColumnIDs`
- [ ] `ShapedData`

### Operators

- [ ] `+`
- [ ] `-`
- [ ] `*`
- [ ] `/`
