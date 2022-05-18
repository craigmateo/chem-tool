# Molecular Geometry

A web-based interactive for chemistry students. Testing electron pair and molecular geometry.

[Demo](https://codepen.io/cfrayne/full/mdXmJPe) 

## Description

A Javascript based web applicataion. 

- User is presented with a molecule.
- User selects electron pair geometry for the given molecule and is given a basic 'skeleton' structure.
- User places atoms, bonds, and electron pairs in the selected structure
- User selects molecular geometry
- Correct/Incorrect feedback is displayed with `alert()` method. JSON object created for more detailed/customizable feedback.

## Getting Started

### Dependencies

* vanilla JS with jQuery cdn
* [Mobius](https://www.digitaled.com/mobius) (*optional*) 

### Installing

* For Mobius, download the zip in the `mobius` subfolder. The Import to Mobius will be an html question.

### Data

* Current data has 31 molecules covering all geometry types
* Molecule data is in JSON format:

```
{
    "Formula":"NF_3",
    "Name":"Nitrogen trifluoride",
    "electron pair Geometry":"Tetrahedral",
    "Central Atom":"N",
    "Terminal Atom 1":"electron pair",
    "Bond 1":"x",
    "Terminal Atom 2":"F",
    "Bond 2":"single",
    "Terminal Atom 3":"F",
    "Bond 3":"single",
    "Terminal Atom 4":"F",
    "Bond 4":"single",
    "Terminal Atom 5":"none",
    "Bond 5":"none",
    "Terminal Atom 6":"none",
    "Bond 6":"none",
    "Molecular Geometry":"Trigonal pyramidal"
}
```

`"Bond 1":"x"` indicates no bond.   

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
