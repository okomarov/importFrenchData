### Description
Matlab function to import data from [Kenneth French's Data Library](http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html), like the series of the Fama and French 3/5 factors, and much more. 

**NOTE**: it does not support a small subset of datasets due to their transposed format. Raise an [issue](https://github.com/okomarov/importFrenchData/issues), if not already reported, to request support for those files, which will be provided depending on the amount of requests.

### Syntax

    importFrenchData() 
      Lists available datasets, their ZIPNAMEs and the description.
    
    importFrenchData(ZIPNAME) 
      Imports into a table the dataset specified by 'ZIPNAME'.

    importFrenchData(...,OUTPATH) 
      Specify name and folder where to save the imported data. By default
      the dataset will be saved under the current directory as '.\ZIPNAME.mat'
