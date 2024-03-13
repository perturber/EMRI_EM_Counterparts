# EMRI_EM_Counterparts

This repository contains data files and workbooks for reproducing the results presented in The Paper "Candidates For Electromagnetic Counterparts of Extreme Mass Ratio Inspirals", Kejriwal et al. (under preparation).

For the Back evolution analysis, the M1 EMRI catalog of Babak et al. (https://arxiv.org/abs/1703.09722) as modified by Pozzoli et al. (https://arxiv.org/abs/2302.07043) can be obtained by contacting the authors here: Federico Pozzoli <fpozzoli@uninsubria.it>. However, we provide the resulting back evolution trajectories for our run of the M1 catalog on Zenodo: 

Resulting files for the REJ1034+396 analysis have filenames "*_Msamples_OOM.txt".

1. The workbook partly uses the FastEMRIWaveforms (FEW) package's 5PNAAK EMRI Waveform Trajectories. It can be installed following the instructions given here: https://github.com/BlackHolePerturbationToolkit/FastEMRIWaveforms

2. Some parts of the workbooks rely on the availability of a GPU.

3. The code for results in Section 2. of The Paper are presented in the Jupyter notebook titled "BackEvolution_Tutorial.ipynb". Corresponding datafiles are present in the folder "BackEvolution".

4. The code for results in Section 3. of The Paper are presented in the Jupyter notebook titled "REJ1034396_EMRI_Tutorial.ipynb". Corresponding datafiles are present in the folder "REJ1034396".
