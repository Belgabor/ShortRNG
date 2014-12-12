ShortRNG
========

A slight enhancement to Kohsuke Kawaguchi's Shorthand RelaxNG format.

http://kohsuke.org/

http://kohsuke.org/relaxng/shorthand/ShortRNG.html


Changes
=======

  * Some fixes regarding shorthand attributes appearing in the output with "type"
  * "ref" can now be used as an attribute, similar to "type":
    
```<element name="abc">
    <ref name="xyz"/>
</element>
```

is functionally equivalent to

```<element name="abc" ref="xyz"/>
```

