# TypeScript

## Specification for NetBeans support for TypeScript

A basic outline of features that are needed in order in which they are needed.

### Phase 1: Set up the GUI infrastructure

#### (a) Extension to Project Properties dialog

<img src="images/typescript-properties.png"/>

Similar to support for SASS and LESS, here the user will
specify the folders in which TS files will be found
and the matching folders where the JS should be generated.

#### (b) Extension to Options window

<img src="images/typescript-options.png"/>

Similar to support for SASS and LESS, here the user will
define the settings related to the TSC tool that will be
used to generate the JS from the TS.

### Phase 2: Generate JavaScript from TS on Save

Use tsc --sourcemap greeter.ts

Using the settings returned from the GUI defined in Phase 1,
automatically generate JS for the currently changed TS file.

### Phase 3: TypeScript Editor

#### (a) New File Type for TypeScript

to be done

Phase 2 above assumes there is support for TS file type,
i.e., TS files should be recognized and when there is a change,
the JS should be generated.

#### (b) Sytax Coloring for TypeScript

to be done

#### (c) Code Completion for TypeScript

to be done



