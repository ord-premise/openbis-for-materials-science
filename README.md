# D4.1 - Fully customized version for Materials Science for openBIS, bringing openBIS to the next level

This deliverable provides a tailored version of openBIS for materials science, featuring custom templates, visualizers, and interface components to streamline data management and analysis. It introduces an [imaging technology](https://openbis.readthedocs.io/en/latest/software-developer-documentation/server-side-extensions/dss-imaging.html) plugin for direct visualization of Nanonis SXM and microscopy DAT files within the openBIS web interface.

## Authors

- Danaila Mihai-Cosmin (ETHZ)
- Fuentes Juan (ETHZ)
- Laskowski Adam (ETHZ)
- Da Costa Lopes Fabio (EMPA)
- Pignedoli Carlo (EMPA)
- Schuler Bruno (EMPA)

## Goal

This deliverable, part of Work Package 4 (WP4), directly addresses the challenge of improving reproducibility and accessibility in materials science experiments and simulations. By customizing openBIS we aim to create a more efficient and standardized data workflow.

In close collaboration with researchers at Empa, we developed:

* New data models and templates specifically designed for materials science data.
* Web application and Graphical User Interface (GUI) components for visualizing and interacting with experimental data.
* Viewers for 2D images and 1D plots, enabling direct analysis of microscopy data.
* Support for automated data import from microscopes, reducing manual data entry and potential errors.
* Interactive tools for working with experimental data within the openBIS environment.

This customized openBIS version natively supports domain-specific file formats widely used in the materials science community, including those within the ETH Domain.


## Achievement

We have designed and implemented new data models and templates within openBIS, tailored to the unique requirements of materials science data. These templates are designed to capture essential metadata and standardize data entry.

This repository enhances openBIS by enabling the storage and visualization of 1D and 2D Nanonis microscopy files as datasets. Key achievements include:

* Development of specialized visualizers and modular interface components for common data formats and plots.
	
* **Interactive 1D Image/Plot Visualization** enables users to visualize data from multiple Nanonis .dat files within a dataset.
* **Interactive 2D Image View** offers a detailed view for individual Nanonis SXM image datasets.
* **Both 1D and 2D viewers** offer interactive controls: 
	* Basic dataset management actions (Upload, New, Save, Delete, Export).
	* Display the main image with zoomable preview.
	* Show associated images (e.g., different channels or processed versions) in a preview strip.
	* Interactive controls for adjusting image display:
		* Channel selection.
		* Axis adjustments (min/max).
		* Color map selection.
		* Scaling options (e.g., logarithmic).
		* Cut-off values.
* **Gallery View for Image Data** provides a visual gallery view for image data allowing users to quickly browse and compare datasets. Features include:
	* Thumbnail previews of image datasets.
	* Pagination and customizable items per page.
	* Options for sorting and filtering data.
	* "Show" and "Export" functionalities directly within the gallery.
	* General information display for the collection of images (e.g., name, default collection view).

* Seamless integration of experimental data within the openBIS lab notebook structure, promoting a comprehensive record of research activities.

* Display and management of metadata associated with datasets, including preview, image, and general metadata fields, enhancing data context and reproducibility.


## External links

[openBIS Imaging Technology](https://openbis.readthedocs.io/en/latest/software-developer-documentation/server-side-extensions/dss-imaging.html)

## Acknowledgements

The [PREMISE](https://ord-premise.org/) project is funded by the [Open Research Data Program](https://ethrat.ch/en/eth-domain/open-research-data/) of the ETH Board.

![image](https://ord-premise.org/assets/img/logos/PREMISE-logo.svg)

![image](https://ethrat.ch/wp-content/uploads/2021/12/ethr_en_rgb_black.svg)
