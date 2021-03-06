![Introduction image](/img/pcdh1_github_0.png)
### Clustering competition binding ELISAs and/or neutralization experiments

Code to cluster fitted sigmoidal curves as described in manuscript "Two point mutations in protocadherin-1 disrupt Andes hantavirus recognition and afford protection against lethal infection" by Megan M. Slough et al.

1. img: Images for readme file
2. input: Experimental data 
   - competition\_ELISAs\_EC1\_mutants: Competition binding ELISAs
   - neutralization\_EC1_mutants: Neutralization data
3. output: Output files generated by scripts
   - competition\_clustering: Output generated by \"clustering.ipynb\"
   - competition\_fitted\_sigmoidal\_readouts.csv: Expected readouts inferred from the fitted sigmoidal
   - competition\_normalized.xlsx: Output generated by \"normalize\_by\_last\_column.ipynb\"
   - competition\_clustering: Output generated by \"clustering.ipynb\"
   - competition\_fitted\_sigmoidal\_readouts.csv: Expected readouts inferred from the fitted sigmoidal
   - competition\_normalized.xlsx: Output generated by \"normalize\_by\_last\_column.ipynb\"
4. scr: script directory
   - normalize\_by\_last\_column.ipynb: Normalize the experimental readouts by the last column ("Control")
      - Input: Raw data in the \"input\" directory
      - Output: Xlsx file with normalized readouts
   - clustering.ipynb: Clustering fitted sigmoidal curves
      - Input: Expected readouts inferred from the fitted sigmoidal
      - Output: Hierarchical clustering of fitted sigmoidals, including k cluster extraction (k goes from 2 to 10)