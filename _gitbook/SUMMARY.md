# Summary

* [Installation](installation/README.md)
   * [On Mac OSX using Homebrew](installation/on_mac_osx_using_homebrew.md)
   * [From a tar.gz](installation/from_a_targz.md)
   * [From source repository](installation/from_source_repository.md)
* [Overview](overview/README.md)
* [Syntax and semantics](syntax_and_semantics/README.md)
   * [Comments](syntax_and_semantics/comments.md)
   * [Local variables](syntax_and_semantics/local_variables.md)
   * [Global variables](syntax_and_semantics/global_variables.md)
       * [Thread local](syntax_and_semantics/thread_local.md)
   * [Assignment](syntax_and_semantics/assignment.md)
       * [Multiple assignment](syntax_and_semantics/multiple_assignment.md)
   * [Control expressions](syntax_and_semantics/control_expressions.md)
       * [Truthy and falsey values](syntax_and_semantics/truthy_and_falsey_values.md)
       * [if](syntax_and_semantics/article.md)
           * [As a suffix](syntax_and_semantics/as_a_suffix.md)
           * [As an expression](syntax_and_semantics/as_an_expression.md)
           * [Ternary if](syntax_and_semantics/ternary_if.md)
           * [if var](syntax_and_semantics/if_var.md)
           * [if var.is_a?(...)](syntax_and_semantics/if_varis_a.md)
           * [if var.responds_to?(...)](syntax_and_semantics/if_varresponds_to.md)
       * [unless](syntax_and_semantics/unless.md)
       * [case](syntax_and_semantics/case.md)
       * [while](syntax_and_semantics/while.md)
           * [break](syntax_and_semantics/break.md)
           * [next](syntax_and_semantics/next.md)
       * [until](syntax_and_semantics/until.md)
       * [&&](syntax_and_semantics/and.md)
       * [||](syntax_and_semantics/or.md)
   * Types and methods
     * Everything is an object
     * The Program
     * Classes and methods
     * Inheritance
     * Modules
     * Generics
     * Structs
     * Constants
     * Blocks, functions and closures
        * Function literal
        * Function pointer
     * alias
   * Type reflection
      * is_a?
      * responds_to?
      * as
      * typeof
   * Attributes
      * @:ThreadLocal
      * @:Packed
      * @:AlwaysInline
      * @:NoInline
      * @:ReturnsTwice
   * Requiring files
   * Low-level primitives
      * pointerof
      * sizeof
      * instance_sizeof
      * declare var
   * Exception handling
   * Compile-time flags
   * Macros
   * C bindings
* Built-in types
   * Bool
   * Integer types
   * Floating point types
   * Char
   * String
   * Symbol
   * Reference
   * Nil
   * Struct
   * Pointer
   * StaticArray
   * Tuple
   * Range
   * Array
   * Hash
   * Regex
