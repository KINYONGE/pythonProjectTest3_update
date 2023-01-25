Installation of the libraries
The libraries used in this script are listed in the requirements.txt file. For the installation, I recommend to use a virtual environment and to install the python libraries directly from your working environment. For my project, I installed the libraries with my Pycharm work environment. It is comfortable and faster.

pip3 --version
pip3 install -r requirements.txt
file
Settings and you go to your virtual environment.
Then you will see Project Settings and choose the Python Interpreter.

Starting the project
To run the script correctly, you need to start the main.py file with two mandatory arguments.

python main.py <base file reference> <tracking file>
To run the script correctly, you need to start the main.py file with two mandatory arguments.

The data is then downloaded from the specified link and saved to a file with a .csv extension.

Example of a project

Voting results for the district of Hlani Mesto Praha:

1. argument: https://www.volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=1&xnumnuts=1100
2. argument: vysledky_Hlavni_Mesto_Praha

Download data from https://www.volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=1&xnumnuts=1100
Export to the file vysledky_Hlavni_Mesto_Praha.csv
Completed.
Finiched.

Partial output :

code;location;registered;envelopes;valid;...
