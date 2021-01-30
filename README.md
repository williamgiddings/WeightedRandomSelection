# WeightedRandomSelection
A quick an easy implementation of WeightedRandomSelection for use in Unity 2020.1.xf+

<h1>!DISCLAIMER</h1>
This will only work in Unity versions 2020.1.xf and above due to the reliance on serializeable generics added in this version.

<h3>Example Usage:</h3>

Initialize in your script then populate in the inspector
```C#
public WeightedCollection<GameObject> WeightedSpellsCollection;
```

To get an item from the collection:
```C#
GameObject ChosenSpell = WeightedSpellsCollection.Get(Random.Range(0, 1));
```

![Example](https://i.imgur.com/hyBDzre.png)
