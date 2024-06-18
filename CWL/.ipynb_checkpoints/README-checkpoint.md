# Variant Calling Workflow

## Dayou Zou

## Description
The workflows leverage popular bioinformatics tools such as BWA, SAMtools, and FreeBayes to perform accurate and efficient variant calling from reads and reference genomes based on Common Workflow Language.

## Usage

To use this workflow, an input file is needed.

The input file should be in YAML format and define the input value. Example input file is given as input_example.yml

After modifying the input file, running following command:
```
cwltool variant_calling_workflow.cwl input_example.yml
```