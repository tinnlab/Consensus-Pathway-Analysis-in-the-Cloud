## Pull Request Template

### Description
<!-- Provide a description of your changes here. If this PR is related to an issue, list the issue number/name here -->
*Provide a description of your changes here. If this PR is related to an issue, list the issue number/name here*

- Reason for Changes: To address the reviewer's comments on the paper submitted to Briefing in Bioinformatics Special Issue: NIGMS SandBox Special Edition.

- Description of Changes: for all notebooks in the module, the following modifications have been made:
	
	+ General changes
		• Changed the names of the submodules.
		• Changed the main figure.
		• Changed the course card image.
		• Added a table of contents to each submodule.
		• Modified the notebook structure.
		• Added comments and annotations to code.

	+ Submodule 01: Processing Expression Data
		• More examples of input data to help users in understanding the required format.
		• Step-by-step screenshots demonstrating data browsing and screening from public repositories. • Detailed instruction on how to perform data normalization and outlier removal.
		• More details about uploading, saving and querying processed data from cloud storage.
	+ Submodule 02: Differential Analysis
		• Complete guideline on how to use four differential analysis techniques to analyze microarray and RNA-Seq data.
		• Description of the parameters needed for differential analysis using different methods (limma, t-test, edgeR, DESeq2) and data types (continuous expression, discrete read counts).
		• Instruction on how to compare and contrast differential analysis results obtained from multiple differential analysis methods and datasets.
		• Details and instruction for new data visualization techniques and result interpretation.
	+ Submodule 03: Processing Pathway Information
		• Details on pathway database structures and how to retrieve pathway information from REACTOME, KEGG, and GO. • Explanation of parameters needed for retrieving pathway information for different species.
	+ Submodule 04: Pathway Analysis
		• Instruction on how to perform pathway analysis using a total of eight methods: ORA, CAMERA, KS test, Wilcoxon test, FGSEA, GSA, SAFE, and PADOG.
		• Details on method assumptions, parameters, and result interpretation.
		• Details about parameters needed to perform pathway analysis using each of the eight methods.
		• More details on result interpretation.
	+ Submodule 05: Meta-analysis
		• Provided more details about the necessary steps for meta-analysis. 
		• More plots for visualization.

### Assignee
<!-- Mention the GitHub username of the user you want to assign this PR to -->
*Assignees: @kyleoconnell-NIH and/or @rosscampbellNIH*

## PR checklist
*Please ensure the following:*
- [x] This comment contains a description of changes (with reason).
- [x] All changes were tested.
- [x] If you've fixed a bug mention the issue number/name.
- [x] Apply approriate tags (e.g. documentation, bug)
