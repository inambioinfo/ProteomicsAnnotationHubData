# ProteomicsAnnotationHub Unit Tests

## Generic tests

- Check that `SourceType`, `DispatchClass` and `RDataClass` match
- Some file types have a base URL on amazon or PRIDE; check these
- ...

## Experiment/data tests

When new data/experiments or even file types will be added, the
procedure to add new AH items will be streamlined, revised, simplified
and hopefully automated. To make sure that any of these updates do not
alter the format/annotation, a set of experiment-specific unit tests
will be set up, that will compare the metadata created in this package
and the metadata extracted from AH.


