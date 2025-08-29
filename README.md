This repository provides a CellProfiler pipeline and a small test dataset for filipin quantification as described in:  

**Eichler, J., Huver, S., Knorr, C.J., Wendling, C., Kobayashi, T., Tomasetto, C., Alpy, F. (2025).  
Methods for Visualizing and Quantifying Cholesterol Distribution in Mammalian Cells Using Filipin and D4 Probes.  
Methods in Molecular Biology, 2888, 101–118.**  
https://doi.org/10.1007/978-1-0716-4318-1_8
## Repository structure
- `pipeline/` → CellProfiler pipeline file (`.cppipe`)  
- `test_dataset/` → Example images for testing the pipeline  
- `README.md` → Documentation  

---

## Usage
1. Install [CellProfiler](https://cellprofiler.org/).  
2. Open the pipeline (`.cppipe`) from the `pipeline/` folder.  
3. Load the test dataset or your own filipin-stained images.  
4. Run the pipeline to quantify filipin fluorescence intensity per cell or per defined region of interest.  

---

## Demo
A small test dataset is included in `test_dataset/` to illustrate the workflow.  

---

## Citation
If you use this pipeline or adapt the method, please cite:  

*Eichler, J., Huver, S., Knorr, C.J., Wendling, C., Kobayashi, T., Tomasetto, C., Alpy, F. (2025).  
Methods for Visualizing and Quantifying Cholesterol Distribution in Mammalian Cells Using Filipin and D4 Probes.  
Methods in Molecular Biology, 2888, 101–118.*  
https://doi.org/10.1007/978-1-0716-4318-1_8
