**SRFIs in the [Tangerine Edition](https://github.com/johnwcowan/r7rs-work/blob/master/TangerineEdition.md)**

- `(srfi 160) ≈ (scheme vector @)` - [SRFI 160: Homogeneous numeric vector libraries](https://srfi.schemers.org/srfi-160/) - see Tangerine Edition for type codes
- `(srfi 159) ≈ (scheme show)` - [~~SRFI 159~~: Combinator Formatting](https://srfi.schemers.org/srfi-159/) - superseded by SRFI 166
- `(srfi 158) ≈ (scheme generator)` - [SRFI 158: Generators and Accumulators](https://srfi.schemers.org/srfi-158/)
- `(srfi 151) ≈ (scheme bitwise)` - [SRFI 151: Bitwise Operations](https://srfi.schemers.org/srfi-151/)
- `(srfi 146) ≈ (scheme mapping) (scheme mapping hash)` - [SRFI 146: Mappings](https://srfi.schemers.org/srfi-146/)
- `(srfi 144) ≈ (scheme flonum)` - [SRFI 144: Flonums](https://srfi.schemers.org/srfi-144/)
- `(srfi 143) ≈ (scheme fixnum)` - [SRFI 143: Fixnums](https://srfi.schemers.org/srfi-143/)
- `(srfi 141) ≈ (scheme division)` - [SRFI 141: Integer division](https://srfi.schemers.org/srfi-141/)
- `(srfi 115) ≈ (scheme regex)` - [SRFI 115: Scheme Regular Expressions](https://srfi.schemers.org/srfi-115/)
- Non-SRFI: `(rnrs bytevectors) ≈ (scheme bytevector)` - adopted from R6RS

**SRFIs in the [Red Edition](https://github.com/johnwcowan/r7rs-work/blob/master/RedEdition.md)**

- `(srfi 135) ≈ (scheme text)` - [SRFI 135: Immutable Texts](https://srfi.schemers.org/srfi-135/)
- `(srfi 134) ≈ (scheme ideque)` - [SRFI 134: Immutable Deques](https://srfi.schemers.org/srfi-134/)
- `(srfi 133) ≈ (scheme vector)` - [SRFI 133: Vector Library (R7RS-compatible)](https://srfi.schemers.org/srfi-133/)
- `(srfi 132) ≈ (scheme sort)` - [SRFI 132: Sort Libraries](https://srfi.schemers.org/srfi-132/)
- `(srfi 128) ≈ (scheme comparator)` - [SRFI 128: Comparators (reduced)](https://srfi.schemers.org/srfi-128/)
- `(srfi 127) ≈ (scheme lseq)` - [SRFI 127: Lazy Sequences](https://srfi.schemers.org/srfi-127/)
- `(srfi 125) ≈ (scheme hash-table)` - [SRFI 125: Intermediate hash tables](https://srfi.schemers.org/srfi-125/)
- `(srfi 124) ≈ (scheme ephemeron)` - [SRFI 124: Ephemerons](https://srfi.schemers.org/srfi-124/)
- `(srfi 121) ⊇ (scheme generator)` - [~~SRFI 121~~: Generators](https://srfi.schemers.org/srfi-121/) - superseded by SRFI 158 in Tangerine Edition
- `(srfi 117) ≈ (scheme list-queue)` - [SRFI 117: Queues based on lists](https://srfi.schemers.org/srfi-117/)
- `(srfi 116) ≈ (scheme ilist)` - [SRFI 116: Immutable List Library](https://srfi.schemers.org/srfi-116/)
- `(srfi 113) ≈ (scheme set)` - [SRFI 113: Sets and bags](https://srfi.schemers.org/srfi-113/)
- `(srfi 111) ≈ (scheme box)` - [SRFI 111: Boxes](https://srfi.schemers.org/srfi-111/)
- `(srfi 101) ≈ (scheme rlist)` - [SRFI 101: Purely Functional Random-Access Pairs and Lists](https://github.com/johnwcowan/r7rs-work/blob/master/RedEdition.md#immutability) **(note the prefix change)**
- `(srfi 41) ≈ (scheme stream)` - [SRFI 41: Streams](https://srfi.schemers.org/srfi-41/)
- `(srfi 14) ≈ (scheme charset)` - [SRFI 14: Character-set Library](https://srfi.schemers.org/srfi-14/)
- `(srfi 1) ≈ (scheme list)` - [SRFI 1: List Library](https://srfi.schemers.org/srfi-1)

**Red Edition finalists**

- `(srfi 140)` - immutable string library
- `(srfi 129)` - titlecase library
- `(srfi 126) (srfi 69)` - hash table libraries

No result:

- `(srfi 130) (srfi 13)` - string libraries, moved to [Selene Docket](https://github.com/johnwcowan/r7rs-work/blob/master/ColorDockets.md#selene-docket-portable-not-srfis-no-implementations)

**String and text libraries**

- `(srfi 152)` - [SRFI 152: String Library (reduced)](https://srfi.schemers.org/srfi-152/) | [Selene Docket](https://github.com/johnwcowan/r7rs-work/blob/master/ColorDockets.md#selene-docket-portable-not-srfis-no-implementations)
- `(srfi 140)` - [SRFI 140: Immutable Strings](https://srfi.schemers.org/srfi-140/)
- `(srfi 135)` - adopted by the Red Edition as `(scheme text)`
- `(srfi 130)` - [SRFI 130: Cursor-based string library](https://srfi.schemers.org/srfi-130/) | [Selene Docket](https://github.com/johnwcowan/r7rs-work/blob/master/ColorDockets.md#selene-docket-portable-not-srfis-no-implementations)
- `(srfi 129)` - [SRFI 129: Titlecase procedures](https://srfi.schemers.org/srfi-129/)
- `(srfi 118)` - [SRFI 118: Simple adjustable-size strings](https://srfi.schemers.org/srfi-118/)
- `(srfi 29)` - [SRFI 29: Localization](https://srfi.schemers.org/srfi-29/srfi-29.html)
- `(srfi 13)` - [SRFI 13: String Libraries](https://srfi.schemers.org/srfi-13/)
- `(srfi 6)` - [SRFI 6: Basic String Ports](https://srfi.schemers.org/srfi-6/) - string builder

**Formatting libraries**

- `(srfi 166)` - [SRFI 166: Monadic Formatting](https://srfi.schemers.org/srfi-166/)
- `(srfi 159)` - adopted by the Tangerine Edition as `(scheme show)`; superseded by SRFI 166
- `(srfi 48)` - [SRFI 48: Intermediate Format Strings](https://srfi.schemers.org/srfi-48/)
- `(srfi 28)` - [SRFI 28: Basic Format Strings](https://srfi.schemers.org/srfi-28/)

**Hash table libraries**

- `(srfi 126)` - [SRFI 126: R6RS-based hashtables](https://srfi.schemers.org/srfi-126/)
- `(srfi 125)` - adopted by the Red Edition as `(scheme hash-table)`
- `(srfi 69)` - [SRFI 69: Basic hash tables](https://srfi.schemers.org/srfi-69/) (mostly superseded by SRFI 125 & Red Edition)

**Record type libraries**

- `(srfi 240)` - [SRFI 240: Reconciled Records](https://srfi.schemers.org/srfi-240/)
- `(srfi 237)` - [SRFI 237: R6RS Records (refined)](https://srfi.schemers.org/srfi-237/)
- `(srfi 150)` - [SRFI 150: Hygienic ERR5RS Record Syntax (reduced)](https://srfi.schemers.org/srfi-150/)
- `(srfi 137)` - [SRFI 137: Minimal Unique Types](https://srfi.schemers.org/srfi-137/)
- `(srfi 136)` - [SRFI 136: Extensible record types](https://srfi.schemers.org/srfi-136/)
- `(srfi 131)` - [SRFI 131: ERR5RS Record Syntax (reduced)](https://srfi.schemers.org/srfi-131/)
- `(srfi 123)` - [SRFI 123: Generic accessor and modifier operators](https://srfi.schemers.org/srfi-123/)
- `(srfi 99)` - [SRFI 99: ERR5RS Records](https://srfi.schemers.org/srfi-99/)
- `(srfi 9)` - [SRFI 9: Defining Record Types](https://srfi.schemers.org/srfi-9/)

**Syntax, binding and control-flow libraries** <a id="user-content-anchor-syntax"/>

- `(srfi 202)` - [SRFI 202: Pattern-matching Variant of the `and-let*` Form that Supports Multiple Values](https://srfi.schemers.org/srfi-202/)
- `(srfi 16)` - [SRFI 16: Syntax for procedures of variable arity](https://srfi.schemers.org/srfi-16/) - case lambda
- `(srfi 11)` - [SRFI 11: Syntax for receiving multiple values](https://srfi.schemers.org/srfi-11/)
- `(srfi 8)` - [SRFI 8: `receive`: Binding to multiple values](https://srfi.schemers.org/srfi-8/)
- `(srfi 5)` - [SRFI 5: A compatible `let` form with signatures and rest arguments](https://srfi.schemers.org/srfi-5/)
- `(srfi 2)` - [SRFI 2: `AND-LET*`: an `AND` with local bindings, a guarded `LET*` special form](https://srfi.schemers.org/srfi-2/)

Withdrawn SRFIs:

- `(srfi 200)` - [~~SRFI 200~~: Pattern Matching](https://srfi.schemers.org/srfi-200/) - abandoned

**Macro transformers**

- `(srfi 147)` - [SRFI 147: Custom macro transformers](https://srfi.schemers.org/srfi-147/) - has a `cond-expand` feature flag

**[Color dockets](https://github.com/johnwcowan/r7rs-work/blob/master/ColorDockets.md) (March 2022)**

Yellow Docket:

- `(srfi 219)`
- `(srfi 213)`
- `(srfi 212)`
- `(srfi 211)`
- `(srfi 210)`
- `(srfi 188)`
- `(srfi 156)` - rejected
- `(srfi 139)`
- `(srfi 61)`
- `(srfi 31)`
- `(srfi 26)`
- `(srfi 8)` - see ["Syntax, binding and control-flow libraries"](#user-content-anchor-syntax)
- `(srfi 5)` - see ["Syntax, binding and control-flow libraries"](#user-content-anchor-syntax); rejected
