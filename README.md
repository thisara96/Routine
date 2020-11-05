# Repository name - Routine Deviation Web App -- Component 04 (IT17081726 - G.G.T.K Edirisinghe)

    This repository contains the source code for Routine Deviation and outlier detection project. Outlier detection is done by identifying behavioral patterns from data.

    ## Directory Structure

    The important files and directories of the repository is shown below

        ├── models : UI related files  
            ├── markov.py : Source code for Markov model
            ├── temporal.py : Source code for Time Series based modelS (Prophet and mean, std models)
        ├── templates : UI related files 
        ├── app.py : Backend of the web app created using Flask
        ├── test.py : test script to add synthetic data to the firebase


    ## Starting the web app 

    ```commandline
    git clone "the repository"
abc
    cd routine-deviationx z xzczxc

    virtualenv -p python3 envname

    source env/bin/activate

    pip install -r requirements.txt

    python app.py
    ```

## Repository name - ESPApp - Android Mobile app -- Component 04 (IT17081726 - G.G.T.K Edirisinghe)

    This repository contains the source code for Routine Deviation - A mobile application developed using Android Studio. The current location real-time view using a map, Routine pattern view, Prediction list for the next day, and the notification for the routine deviation and other necessary notifications are enabled.

    Use any code editor to view the codings. Android Studio Project

## Repository name - ESPCode - Code to the ESP32 Module -- Component 04 (IT17081726 - G.G.T.K Edirisinghe)

    This repository contains the source code for the Routine Deviation - ESP32 module. The location data is been fetch using BLE technology and transferred to the database using WiFi technology. The necessary libraries are as follows. 

    Coding done using arduino IDE

        ---- Libraries used 

        IOXhop_FirebaseESP32.h
        IOXhop_FirebaseStream.h
        WiFi.h
        WiFiClient.h
        WiFiServer.h
        WiFiUdp.h
        NTPClient.h
        WiFiUdp.h
