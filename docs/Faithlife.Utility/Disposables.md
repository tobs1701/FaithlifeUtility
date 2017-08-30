# Disposables class

A collection of disposable objects, disposed in reverse order when the collection is disposed.

```csharp
public sealed class Disposables : IDisposable, IEnumerable
```

## Public Members

| name | description |
| --- | --- |
| [Disposables](Disposables/Disposables.md)() | Initializes a new instance of the [`Disposables`](Disposables.md) class. |
| [Disposables](Disposables/Disposables.md)(…) | Initializes a new instance of the [`Disposables`](Disposables.md) class. |
| [Add](Disposables/Add.md)(…) | Adds the specified disposable. |
| [AddRange](Disposables/AddRange.md)(…) | Adds the specified disposables. |
| [Dispose](Disposables/Dispose.md)() | Disposes all added disposables, in reverse order. |

## Remarks

This class is thread-safe. Null disposables are legal and ignored. Objects cannot be added to the collection after it has been disposed. The collection cannot be enumerated.

## See Also

* namespace [Faithlife.Utility](../Faithlife.Utility.md)
* [Disposables.cs](https://github.com/Faithlife/FaithlifeUtility/tree/master/src/Faithlife.Utility/Disposables.cs)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->