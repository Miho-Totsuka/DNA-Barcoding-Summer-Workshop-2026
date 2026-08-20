# Day 5 — DNA Subway Analysis and Phylogenetic Trees

## What I Learned

On Day 5, I learned how DNA sequence data can be analyzed on a computer to investigate the identity and relationships of organisms.

We used DNA Subway, a bioinformatics platform that helps organize DNA barcoding data and compare sample sequences with reference sequences from known organisms.

I learned how to read a phylogenetic tree. In this kind of tree, samples that cluster closely together have more similar DNA sequences, while samples that are farther apart are less similar.

## Analysis

We analyzed both plant and ant DNA sequences using DNA Subway.

For the plant dataset, our numbered samples were compared with reference plant sequences. DNA Subway generated a phylogenetic tree showing where each sample was placed relative to known species.

We also analyzed the ant dataset in the same way. This allowed us to compare our unknown ant sequences with reference ant sequences and see which samples grouped with known ant species.

## Methods

The general process was:

1. Obtain DNA sequence data from the samples.
2. Upload and analyze the sequences in DNA Subway.
3. Compare the sample sequences with reference sequences from known organisms.
4. Generate phylogenetic trees.
5. Examine where each unknown sample appeared in the tree.
6. Interpret possible identifications and relationships based on clustering patterns.

## Results

For the plant analysis, the phylogenetic tree showed that our samples were distributed among a wide range of plant reference sequences. Some samples clustered near groups such as Bellevalia, Muscari, Rosa, Malva, Nepeta, Artemisia, and Achillea. This showed that the plant dataset contained multiple different kinds of plants rather than a single closely related group.

![Plant Phylogenetic Tree](figures/plant_phylogenetic_tree.png)

For the ant analysis, some samples clustered relatively close to known reference groups. For example, one sample was placed near Tetramorium caespitum, another near Lasius neoniger, and several samples were positioned close to Camponotus pennsylvanicus. Other samples grouped in less clear positions and were not matched as directly to one obvious reference species.

One especially interesting result was that one sample appeared near plant reference sequences rather than ant reference sequences. This suggests that the sequence may have had contamination, a labeling problem, or low-quality data, and it showed me that sequence results must be interpreted carefully.

![Ant Phylogenetic Tree](figures/ant_phylogenetic_tree.png)

## What I Learned From the Results

From these results, I learned that DNA identification is not just about obtaining a sequence. The sequence must also be compared with reference data and interpreted carefully.

If a sample clusters close to a known reference species, that gives evidence that the sample may belong to that species or to a closely related organism. However, the result is not always perfectly clear. Some samples may not cluster strongly with a single species, and unusual placements can happen because of contamination, sequencing problems, or limited reference data.

This helped me understand that bioinformatics is both analytical and interpretive. A phylogenetic tree is useful evidence, but it still has to be evaluated carefully.

## Reflection

This was one of the most interesting parts of the workshop because it connected all of the previous laboratory work to computational analysis.

Earlier in the workshop, we extracted DNA, purified it, amplified it with PCR, and examined it with gel electrophoresis. On Day 5, we finally used sequence data to investigate real biological relationships.

The overall workflow was:

`Biological Sample → DNA Extraction → PCR → Gel Electrophoresis → Sequencing → DNA Subway Analysis → Phylogenetic Tree → Biological Interpretation`

This helped me understand how laboratory biology and bioinformatics work together in DNA barcoding. I especially liked seeing how sequence data could be turned into a tree that could be interpreted scientifically, while also learning that not every result is straightforward.
