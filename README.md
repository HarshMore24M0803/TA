# ERP Clean Script

This script processes an ERP downloaded file, which is assumed to be a `.csv` file. It cleans the data, processes the amounts, and creates separate CSV files for cleaned and discarded values. It also adds debit, credit, and balance columns to the cleaned data.
Keep the script in the same file as the data file.


## Prerequisites
Before running the script, make sure Python and `pip` are installed on your system.

### Install Python and pip
sudo apt update
sudo apt install python3 python3-pip -y

### Install the Dependencies
pip install -r requirements.txt


Run ./erpclean or ./erpclean --help for more info


