# Class VS File
## no public class required in file.
`javac NoPublicClassRequired.java` output file `NoPublicClassRequired.class`

## multiple classes could be in the same file.
`javac MultipleClasses.java` output files `MultipleClass1.class` and `MultipleClass2.class`

## at most one class is public
`javac AtMostOnePublicClass.java` output files `AtMostOnePublicClass.class` and `NotPublicClass.class`

## public class must have same name of the file
`javac PublicClassWithSameName.java` output file `PublicClassWithSameFileName.class`
`javac SorryMyNameIsDifferent.java` output `error: class SorryMyNameIsDifferent is public, should be declared in a file named SorryMyNameIsDifferent.java`