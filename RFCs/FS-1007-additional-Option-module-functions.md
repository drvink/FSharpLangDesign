# F# RFC FS-1007 - Additional Option module functions

The design suggestion [Additional Option module functions](https://fslang.uservoice.com/forums/245727-f-language/suggestions/6672880-add-a-option-getordefault-method-as-a-curryable-al) has been marked "approved in principle".  
This RFC covers the detailed proposal for this suggestion.

[Discussion thread](https://github.com/fsharp/FSharpLangDesign/issues/60)

* [x] Approved in principle
* [ ] Details: [under discussion](https://github.com/fsharp/FSharpLangDesign/issues/60)
* [ ] Implementation: not yet submitted

### Introduction

Additional functions to `Option` module

Proposed functions:

#### Default if `None`

Gets the value associated with the option or the supplied default value

```fsharp
val getOrDefault : 'a -> 'a option -> 'a
val defaultIfNone : 'a -> 'a option -> 'a
val orDefault : 'a -> 'a option -> 'a
val fill : 'a -> 'a option -> 'a // ExtCore.Option.fill
```

#### Option.map overload

```fsharp
val map2: ('a -> 'b -> 'c) -> 'a option -> 'b option -> 'c option
```

```fsharp
val map3: ('a -> 'b -> 'c -> 'd) -> 'a option -> 'b option -> 'c option -> 'd option
```


### Under discussion:

- `inline` modifier
- exact additions
  - study adopting `ExtCore.Option` module declared in https://github.com/jack-pappas/ExtCore/blob/5221f4e67a93cffdb85203f3ae403a6052bcfbc0/ExtCore/Pervasive.fs#L810

### Naming 

The name of the functions has not been finalized.  Some of the suggestions are:

- `getOrDefault`
   * `getOrElse`

### Performance considerations

The standard range of performance considerations for F# library functions apply.

### Testing considerations

The standard range of testing  considerations for F# library functions apply.
