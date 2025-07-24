## Type I CRISPR-Cas immunity primes type III spacer acquisition
The respository contains code used in Smith and Fineran 2025, Cell Host Microbe

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

