# SRA Toolkit
How to download SRA toolkit and commands to download data

1. Download the toolkit for Mac
```
curl -OL sratoolkit.tar.gz http://ftp-trace.ncbi.nlm.nih.gov/sra/sdk/current/sratoolkit.current-mac64.tar.gz
```
2. Unzip the toolkit
```
tar vxzf sratoolkit.tar.gz
```
3. Add to $PATH to use commands
Example of sratoolkit.<release>-<platform> could be sratoolkit.2.4.0-1-mac64
```
export PATH=$PATH:/location/of/sratoolkit.<release>-<platform>/bin
```
4. [Configure](https://github.com/ncbi/sra-tools/wiki/03.-Quick-Toolkit-Configuration) the tool based on your use case.
5. Run commands.
