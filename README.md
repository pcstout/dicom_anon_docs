# Dicom Anonymizer Tool Installation and Operation

## Installation

### Prerequisites

1. Java Runtime Environment version 1.8+ [Available Here](https://java.com)

### Dicom Anonymizer Tool

1. Download the Dicom Anonymizer Tool [here](http://mirc.rsna.org/download/DicomAnonymizerTool-installer.jar)
2. Open a command prompt and change directory to the folder were you saved the above file.
3. Execute `java -jar DicomAnonymizerTool-installer.jar`.
4. Choose a folder to install the files to and click `Open`.

### Java Advanced Imaging ImageIO Tools

1. [Download from Here](https://mircwiki.rsna.org/index.php?title=Java_Advanced_Imaging_ImageIO_Tools)
2. Run the installer (for Winodws) or extract the files into the Dicom Anonymizer Tool install directory.

## Operation

Anonymize a folder that contains DICOM files.

1. Open a command prompt and change directory to the folder were you installed the tool.
2. Execute `java -jar DAT.jar -da dicom-anonymizer.script -dpa dicom-pixel-anonymizer.script -in c:\my_dicoms -out c:\my_anon_dicoms` (change `my_dicoms` to the location of your DICOMs and `my_anon_dicoms` to a folder where the anonymized files will be stored.)