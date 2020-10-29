---
title: "Get a list of "
teaching: 10
exercises: 20
questions:
- "How to find genotypic data for the given germplasm?"
- "How to search for sequence variants between two selected germplasm?"
- "How to view genome within a given region?"
objectives:
- "Providing a step by step demonstration on how to"
keypoints:

---

## Step #1: Go to the Lentil Genotype Matrix Tool
When you land on the Knowpulse home page, click on "Genotypes" at the top of the page, this will scroll you down to the genotypes section. Then you want to click on "Lentil Genotypes" to access the Lentil Genotype Matrix Tool.
![Screenshot of main code listing](../fig/gmatrix-poly-region.front-1.png)

## Step #2: Find genotypic data for your reference germplasm
Enter the name of each germplasm you are interested in, `ILL 8006` and `CDC Milestone` in this case, by typing it in the textfield labelled germplasm. Then check the correct species is selected to the right of the textbox. To add more then one germplasm, click the `green +` button.

After entering "ILL 8006" in the top germplasm textfield, you will notice that it autocompleted as you type. Then click the `green +` button and enter "CDC Milestone" in the second textfield which appears.
Each time you click the `green +` button or search, the genotypic data for the listed germplasm will be shown.
![Screenshot of main code listing](../fig/gmatrix-poly-region-2.png)

## Step #3: Restrict the Sequence Variants to polymorphic between your germplasm
Underneath germplasm, there is a filter to restrict to polymorphic variants. This filter compares two germplasm and only shows variants with different genotypic calls.

For our example, we would select `ILL 8006` in the first drop down and `CDC Milestone` in the second drop-down to see only sequence variants with differing genotypes (i.e polymorphic variants) between these two germplasm.
Click Search to see the results.
![Screenshot of main code listing](../fig/gmatrix-poly-region-3.png)

## Step #4: Restrict to you trait-implicated Region of the Genome
The second section of the filter criteria available for the genotype matrix allows you to enter the region of the genome you are interested in. Once you click search, the genotype matrix will only show sequence variants found in this region. In our example, the region of interest is `LcChr4:1875000-2075000`. To enter this, we place `LcChr4` for the `Sequence Name`, `1875000` for the start position and 2075000 for the end position.
![Screenshot of main code listing](../fig/gmatrix-poly-region-4.png)

## Step #5: (Optionally): Restrict to specific variants.
Say you are interested in a specific set of variants and would like to see that subset. You can enter the specific variant names by expanding the `Additional Filter criteria` section then clicking Search.
![Screenshot of main code listing](../fig/gmatrix-poly-region-5.png)
