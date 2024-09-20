# ``extern()``
``extern()`` is a part of the Evalate standard library that allows you to run C++ code through Evalate. Although it is still integrated into Evalate's interpreter itself,
the header file will mirror here every release.

## Syntax
``extern()`` accepts arguments and converts them into C++ variables for you to use. Here is how the conversions work:

- ``int`` -> ``int``
- ``string`` -> ``std::string``
- ``double`` -> ``double``
- ``type`` -> not converted (not supported)

```cpp
extern(<arguments>) {
  // C++ code goes here

  std::cout << "this is C++\n";
}
```

## Planned Stuff
- Add support for using ``return``, meaning you can pass arguments back into Evalate
