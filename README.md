# Description
The directories `protocols` and `raw-data` respectively contain the MRI settings and sample data for multi-parameter mapping (MPM) to be used with the hMRI-toolbox (http://hmri.info).  
The data set is published in the context of the following article:

[Callaghan, M. F., Lutti, A., Ashburner, J., Balteau, E., Corbin, N., Draganski, B., ... & Weiskopf, N. (2019). Example dataset for the hMRI toolbox. Data in brief, 25, 104132.](https://doi.org/10.1016/j.dib.2019.104132)

which is published under a [CC BY 4.0-Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license.

# Sample dataset (raw-data)
In the `raw-data` directory, a sample dataset is provided as reference data to explore the functionalities of the hMRI-toolbox. The corresponding acquisition protocol can be found in `hmri_sample_dataset_protocol_800um_64ch.pdf` in the
`protocols` directory.

# Example MRI protocols (protocols)
In the `protocols` directory, the following are included:
- several example MRI protocols: standard MPM protocol using customised Siemens sequences, as well as MPM protocol implemented using Siemens and Philips product sequences
- setup for Siemens 3T MRI and a tutorial.

Please be aware that we provide these protocols and information without any warranty. They must be considered work-in-progress, possibly non-optimal protocols and information.

### Siemens protocol with customized sequences:
`MPM_protocol_customized_seq_SIEMENS.pdf`

### Siemens protocol with vendor sequences:
`MPM_protocol_vendor_seq_SIEMENS_settings.pdf`
`MPM_protocol_vendor_seq_SIEMENS_setup_tutorial.pdf`

### Philips protocol:
ExamCard for quick installation (zipped): 
`MPM_protocol_Philips.ExamCard.zip` 

Text files with detailed settings for each protocol to double-check/for manual setup: 
`MPM_protocol_Philips_settings_as_textfiles.zip`

### Operational procedure (especially for use with vendor sequences - either Siemens or Philips):
`MPM_protocol_operational_procedure.pdf`
