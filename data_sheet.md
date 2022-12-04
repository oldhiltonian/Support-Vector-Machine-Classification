# Datasheet Template

## Motivation

The aim is to identify subsets of proteins that are discriminant between the classes of Downs Syndrome and Control mice, and to help future predictice models in the field of genetics. 

Creators:
- Clara Higuera Department of Software Engineering and Artificial Intelligence, Faculty of Informatics and the Department of Biochemistry and Molecular Biology, Faculty of Chemistry, University Complutense, Madrid, Spain. 
- Katheleen J. Gardiner, creator and owner of the protein expression data, is currently with the Linda Crnic Institute for Down Syndrome, Department of Pediatrics, Department of Biochemistry and Molecular Genetics, Human Medical Genetics and Genomics, and Neuroscience Programs, University of Colorado, School of Medicine, Aurora, Colorado, USA. 
- Krzysztof J. Cios is currently with the Department of Computer Science, Virginia Commonwealth University, Richmond, Virginia, USA, and IITiS Polish Academy of Sciences, Poland. 
 
## Composition

- Instances are individual mice. 
- Classes:

    c-CS-s: control mice, stimulated to learn, injected with saline (9 mice)

    c-CS-m: control mice, stimulated to learn, injected with memantine (10 mice)

    c-SC-s: control mice, not stimulated to learn, injected with saline (9 mice)

    c-SC-m: control mice, not stimulated to learn, injected with memantine (10 mice)

    t-CS-s: trisomy mice, stimulated to learn, injected with saline (7 mice)

    t-CS-m: trisomy mice, stimulated to learn, injected with memantine (9 mice)

    t-SC-s: trisomy mice, not stimulated to learn, injected with saline (9 mice)

    t-SC-m: trisomy mice, not stimulated to learn, injected with memantine (9 mice)

- Some fields contain null values.
- No data is confidential.

## Collection process

- No information is available regarding the collection process.

## Preprocessing/cleaning/labelling

- Preprocessing was done by dropping instances with null values. Other preprocessing was simply to give more descriptive names to the classes. 
 
## Uses

- Drawing conclusion about genetic disorders among other mammals, not just in mice. 
- Note that this dataset should not be used in any way to build models for use within the healthcare industry. No prediction of human Downs Syndrome should be made off of this dataset and this could invariably lead to discriminatory practices. 

## Distribution

- Distributed via Kaggle 
- Distributed under the CC0: Public Domain license. 

## Maintenance

- No maintenance specified.
