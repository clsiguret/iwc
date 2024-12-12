## Contiging Solo:

Generate assembly based on PacBio Hifi Reads.


### Inputs


1. Hifi long reads [fastq]
2. K-mer database [meryldb]
3. Genome profile summary generated by Genomescope [txt]
4. Homozygous Read Coverage. Optional, use if you think the estimation from Genomescope is inacurate. 
5. Genomescope Model Parameters generated by Genomescope [tabular]
6. Database for busco lineage (recommended: latest)
7. Busco lineage (recommended: vertebrata)
8. Name of first assembly
9. Name of second assembly


### Outputs

1. Primary assembly
2. Alternate assembly
3. QC: Bandage image for the raw unitigs
4. QC: BUSCO report for both assemblies
5. QC: Merqury report for both assemblies
6. QC: Assembly statistics for both assemblies
7. QC: Nx plot for both assemblies
8. QC: Size plot for both assemblie