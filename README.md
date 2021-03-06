F# Language Design RFCs 
=================

RFCs and docs related to the F# langauge design process. The Process:

1. Use [F# Language User Voice](http://fslang.uservoice.com) to submit ideas, vote on them and discuss them.

2. Ideas which get "approved in principle" get an [RFC entry](https://github.com/fsharp/FSharpLangDesign/tree/master/RFCs) based on the [template](https://github.com/fsharp/FSharpLangDesign/blob/master/RFC_template.md), and a corresponding [RFC discussion thread](https://github.com/fsharp/FSharpLangDesign/issues)

   There is currently a backlog of approved ideas. If an idea has been approved and you'd
   like to accelerate the creation of an RFC,  send a PR creating the RFC document for any approved-in-principle issue.
   First in first served.  To "grab the token" send a PR doing nothing but creating or naming the RFC file, and
   then fill in the further details with additional commits to the PR.

3. Implementations and testing are usually submitted to the [visualfsharp](https://github.com/Microsoft/visualfsharp/pulls) repository and then integrated to [fsharp](https://github.com/Microsoft/fsharp/fsharp) and  [FSharp.Compiler.Service](https://github.com/Microsoft/fsharp/FSharp.Compiler.Service)

Completed RFCs

* [F# RFC FS-1005 - Underscore Literals](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1005-underscores-in-numeric-literals.md)
* [F# RFC FS-1008 - Struct Records](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1008-struct-records.md)
* [RFC FS-1002 Cartesian product function for collections](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1002-cartesian-product-for-collections.md)
* [F# RFC FS-1009 - Allow mutually referential types and modules over larger scopes](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1009-mutually-referential-types-and-modules-single-scope.md)
* [F# RFC FS-1010 - Add Map.count](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1010-add-map-count.md)
* [F# RFC FS-1013 - Enable FSharp.Reflection functionality in PCLS](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1013-enable-reflection-functionality-on-portable-profiles.md)

Nearing-Completion RFCs

* [F# RFC FS-1006 - Struct Tuples and Interop with C# 7.0 Tuples](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1006-struct-tuples.md)
* [F# RFC FS-1012 - Support for caller info argument attributes (CallerLineNumber, CallerFileName, CallerMemberName)](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1012-caller-info-attributes.md)
* [F# RFC FS-1014 - Single case struct unions](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1014-struct-unions-single-case.md)

Open RFCs

* [F# RFC FS-1001 - String interpolation](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1001-StringInterpolation.md)
* [F# RFC FS-1003 - Add nameof Operator](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1003-nameof-operator.md)
* [F# RFC FS-1004 - Result type](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1004-result-type.md)
* [F# RFC FS-1007 - Additional Option module functions](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1007-additional-Option-module-functions.md)
* [F# RFC FS-1011 - Warn when recursive function is not tail-recursive](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1011-warn-on-recursive-without-tail-call.md)
* [F# RFC FS-1015 - Support for "fixed"](https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1015-support-for-fixed.md)

