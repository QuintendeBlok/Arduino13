Welcome to the Arudino repository. Here you will find out how to reproduce our findings reported in the Report {Placeholder}.

📄 Final Report:
- The full description of this project (research question, method, results and conclusions) can be found here:

The structure of the repository is as follows:
- Final_Report.pdf must be READ, it contains a whole complete and sufficient set of instructions to reproduce the results.
- Files starting with Data correspond to the raw data of the experiment for each data collection place
- Files starting with Plot are used to plot the data using python
- Files with (C++) at the end are the arduino code that must be utilised in the correct order to reproduce the results (see the Final_Report.pdf)

├── Code uitlezen sensoren (C++)         # Reads the sensors and writes measurements to the SD card
├── Reading the SD card (C++)            # Reads back and prints the data stored on the SD card
├── Delet the existing file (C++)        # Deletes an existing file from the SD card before a new run
├── Code plotten resultaten (python)     # Plots the environmental sensor data
├── Data_BBG.csv                         # Measurement data – [BBG location]
├── Data_MIN.csv                         # Measurement data – [MIN location]
├── Plot_BBG_data.png                    # Plot of the BBG data
├── Plot_MIN_data.png                    # Plot of the MIN data
├── Final_Report.pdf                     # Report outlining the steps needed to reproduce our result
└── README.md
