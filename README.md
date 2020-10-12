# ExportFromSasDataset

Allows the exporting of a SAS dataset to a delimited file with more formatted values as well as labels

### Requires
#### Sas Local Provider (OleDB/ODBC)
###### (Note: SAS local provider is already installed if you have SAS EG or other local SAS software installed)
#### .NET Core 3.1 (or higher)

# ExportFromSasDataset
## USAGE:
## Normal scenario:
##    ExportFromSasDataset --DataSet SHOES --Formatted --Lib c:\temp --Labels --Work C:\temp\ExportFromSasDataset
## All datasets:
##  ExportFromSasDataset --Formatted --Lib c:\temp --Labels --Work C:\temp\ExportSasDataset
# 
###   -l, --Lib           Required. The physical directory where the SAS datasets are located
###   -d, --DataSet       The name of the SAS dataset
###   -w, --Work          Required. The physical directory for the work area
###   -f, --Formatted     Export the values as formatted
###   -v, --Labels        Convert variable names to labels
###   -m, --ExportMeta    Exports the metadata definitions
###   --help              Display this help screen.
###   --version           Display version information.
