# STL

### Passing STL container by reference

```cpp
void SomeClass::someFunction(std::vector<char>& changable) { ... } //no copy but can be changed
void SomeClass::otherFunction(std::vector<char> const& immutable) { ... } //no copy and can't be changed
```