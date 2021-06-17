========================
Compound names
========================

There are several ways in which one can define the name of a given material and/or chemical compound. In the HybriD\ :sup:`3` database, our objective is to support as many searchable alternative names as possible for a given compound, mapping (where possible) community conventions.

--------------------------
Definition of a "material"
--------------------------

We generally define a "material" as a single-phase chemical compound, that is, a material that can be made homogeneously beginning from the atomic scale. Composite materials with separate phases at a scale larger than the scale of a few nanometers would thus be defined as two separate materials. However, in hybrid organic-inorganic semiconductors, structural units can be large and the difference between a single-phase material and two separate materials in a composite can be somewhat undefined. Where necessary (e.g., for so called quasi-twodimensional hybrid perovskites or "2.5D" hybrid perovskites), well-defined "materials" that are nanostructured will be included in the database pragmatically.

-----------------
Naming a compound
-----------------

The HybdriD\ :sup:`3` supports multiple names for the same compound, reflecting the fact that there are multiple naming conventions in the chemical and materials science literature. Some of them overlap, others may not even be unique between different compounds. Our core objectives are to provide names that are, at least in their combination, unique, but even more importantly to make a given compound findable by users who are potentially using different conventions.

The present version of the database (June 2021 and previously) uses short compound names that are inspired by chemical formulae but that essentially reflect abbreviations commonly used in the perovskite literature. 

For instance, the 3D hybrid perovskite methylammonium lead iodide appears first under the name of "MAPbI3", using the frequent abbreviation "MA" for the methylammonium cation. 

In a separate field, alternate names for the same compound are provided, e.g., "MAPI" (short form used in the community), "(MA)PbI3", "CH3NH3PbI3" or, indeed, "Methylammonium lead iodide". These are not the only possible names for methylammonium lead iodide, but will give a user a reasonable chance to identify the compound in question with specificity. 



However, the "MAPbI3" convention for the "main" compound name quickly becomes ambiguous for more complex compounds. Going forward (post June 2021) we therefore will adopt the following strategy for naming compounds and for providing alternate names:
