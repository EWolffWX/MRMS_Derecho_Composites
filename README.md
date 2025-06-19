# MRMS_Derecho_Composites
Jupyter notebook to create composite images of derechos using MRMS data from each hour

Notes:
1) This code will download files from AWS directly to your local machine. Some local storage will be neccessary. Each file is approximately 500 kB
2) This code was originally only set up to work for a single UTC day. If your event runs from 20 UTC to 5 UTC the following day, for example, please use the "modified" version of the code.
3) The NSSL archive on AWS is only available for 10/14/2020-present.
4) Some sections of the code create new directories for your data automatically. These assume you are using a Linux or Mac environment. If you are using Windows, either modify these sections or remove them and create the folders you need manually
