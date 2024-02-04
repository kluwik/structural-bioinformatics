# Class 05. Torsion angles in PyMol

## Measure torsion angles

1. Download PDB ID *1FZY* form Protein Data Bank.
2. Open PyMol and load the downloaded structure: *File* → *Open*.
3. Remove water molecules and chain A by typing the following command in the PyMol command line (under the log and above the main scene): `remove chain A resn hoh`.
    
    P.S. This is an example when the structure contains two copies of the protein (in asymmetric unit), while the functional entity is a single protein. So we need to leave either of the two protein molecules. You may take a look at the section about unresolved entities in the PDB structure file to understand, why we removed chain A, but not B.
    
4. Display the sequence of the protein: *Display* → *Sequence*. It will appear under command line.
Select residues I11, Q12, A13 by clicking on them sequentially in the sequence. The selection with the name *sele* will appear in the right sidebar.
5. Display the selected residues in ball-and-sticks representation for easier picking of atoms: in the right sidebar click on *S* button of *sele*. Click *sticks.*
Couple of adjustments to display balls: 
*Settings* → *Lines and Sticks* → *Ball and sticks ratio → 1.5*
*Settings* → checkmark on *Ball and sticks* 
6. Hide the protein ribbons: in the right sidebar click on H button of *1fzy* and choose *cartoon*.
7. Now we are ready to pick atoms for measuring torsion angles! Adjust the view to make atom picking comfortable. If you get lost in the scene, center the view on the residues by typing the command: `center resi 12`
8. Go to *Wizard → Measurement*. In the bottom of the right sidebar click on *Distances* and select *Dihedrals*. PyMol will suggest you (a message will appear under the command line) to pick four atoms to measure a torsion angle. Choose wisely! Remember what atoms form Phi and Psi angles (consult the slides). To understand which atom belongs to which residue, look at the side chains of the residues. Pick atoms sequentially by clicking on them with the left mouse button (every time you pick an atom, a pink square dot appears on it). 
After you pick four atoms, a dihedral angle will be visualized. After that you can pick another four atoms to visualize another dihedral angle.
When you finish with measuring torsion angles, click *Done* in the right sidebar.
Profit!

## Optional and fun: playing with torsion angles

To get a feeling of torsion angles, let’s disrupt them!

Display the protein ribbons and make them transparent: click *S* button of *1fzy* and choose cartoon, then type `set cartoon_transparency, 0.7`

Go to *Mouse* → *2 Button editing*. Pick an alpha-carbon atom of Q12 - a white cage will appear. Hold *Ctrl* and rotate with the left mouse button the part of a protein to the left/right of the alpha-carbon. Zoom out the scene and check how the structure is altered with different torsion angles.
