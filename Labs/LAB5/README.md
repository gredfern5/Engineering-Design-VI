# Lab 5 | Paho-MQTT
## George Redfern
### Lab Instructions:
- Go to the GitHub repository Lesson 5
- Install Paho-MQTT
- Change directory to the iot repository
- Update the repository with `git pull`
- Change directory to Lesson 5
- Run `python3 subcpu.py` on one terminal
- Run `python3 pubcpu.py` on another terminal

### Step 1: Installations

- Download and install Mosquitto from [Mosquitto official website](https://mosquitto.org/download/).
- Open **System Properties** and click on **Environment Variables**.
- In **System Variables**, select `Path` and click **Edit**.
- Click **New** and enter the Mosquitto installation path: `C:\Program Files\Mosquitto`.
- Click **OK** to save changes.

### Step 2: Setting Up Terminals and Running Scripts

- **Navigate to the project directory**:  
  I run:  
  `cd ~/iot`

- **Pull the latest updates**:  
  I update my local repository with:  
  `git pull`

- **Navigate to the lesson5 directory**:  
  I change to the `lesson5` folder with:  
  `cd lesson5`

- **Run the script**:  
  I attempt to run the script with:  
  `python pubcpu.py`  
  But it fails due to the missing `paho-mqtt` module.

- **Install the missing module**:  
  I install the `paho-mqtt` package with:  
  `pip install paho-mqtt`

- **Run the script again**:  
  After installing the module, I run the script again with:  
  `python pubcpu.py`  
  The script runs successfully, and I see the output.

  ![image](https://github.com/user-attachments/assets/58559392-0b50-47df-87b0-2af5d9ce0d73)

  # Summary
In this lab, I learned how to update a repository, install missing Python packages, and successfully run a Python script that uses the paho-mqtt library to interact with MQTT.

I pledge my honor that I have abided by the Stevens Honor System- George Redfern
