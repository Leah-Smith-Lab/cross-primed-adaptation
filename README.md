## Type I CRISPR-Cas immunity primes type III spacer acquisition
This respository contains code used in [Smith and Fineran 2025](https://doi.org/10.1016/j.chom.2025.07.021), <i>Cell Host & Microbe </i>

## Structure
scripts/ - R Markdown (.Rmd) files used to analyze data / produce figures.

## Usage

1. **Download** the `Data_analysis` folder from Mendeley Data (~5 GB) https://doi.org/10.17632/n33vch8vjc.1   
   The folder contains raw and semi-processed data needed to reproduce the analyses/figures.  
   The folder is structured containing the required `input/` and `output/` subdirectories.

3. **Download** the R Markdown (.Rmd) files and open in R Studio.  
   The global working directory is set to the `Data_analysis` folder.
   Adjust as needed to make this folder your home working directory.  
   This ensures the scripts can find inputs and save outputs in the right subfolders.

5. **Run All** chunks in the R Markdown file(s).  
   The outputs (excel files; CSV files; PDFs of plots etc.) will be saved to the specified subdirectories.

   ## Usage
   If you re-use code from this analysis please cite: <br>
   Smith, L. M. and P. C. Fineran (2025). "Type I CRISPR-Cas immunity primes type III spacer acquisition." Cell Host & Microbe 33(9): 1561-1576.e1566. https://doi.org/10.1016/j.chom.2025.07.021
	

   

