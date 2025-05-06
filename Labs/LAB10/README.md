# Lab 10 | Blockchain
## George Redfern
### Lab Instructions:

Review lesson 10 in the GitHub repository.
- Run hash_value.py twice and compare results
- Run snakecoin.py
- Run snakecoin-server-full-code.py on Terminal 1 and mine a new block on Terminal 2
- Clone Python blockchain app and uncomment the last line of node_server.py
- Run node_server.py on Terminal 1 and run app.py on Terminal 2  </br>

Document results to your GitHub repository.

---
### Part 1: Running hash_value.py

I ran the hash_value.py program twice by executing the following code: 
```
$ cd ~/iot/lesson10
$ cat hash_value.py
$ python hash_value.py
$ python hash_value.py
```
![image](https://github.com/user-attachments/assets/8430fd27-878e-4f7e-8238-7effcc8dd3fd)
---

The cat command was used to display the contents of the file prior to executing the program. The program’s objective was to generate hash values for a variety of variables.
Notably, the hash values for 1, 1.0, and 3.14 remained consistent across both executions. However, the hashes for the string "Python", a tuple containing vowels, and a Person object varied between runs.

---

### Part 2: Running snakecoin.py

I ran snakecoin.py by executing the following code: 
```
$ cd ~/iot/lesson10
$ cat snakecoin.py
$ python3 snakecoin.py
```
![image](https://github.com/user-attachments/assets/16db7377-17af-4c30-a177-1a43e02e582f)

Pictured above are the results of the blocks added to the blockchain


### Part 3: Running snakecoin-server-full-code.py

In order to run the SnakeCoin server, I ran the following code on the first terminal: 
```
pip install flask
cat snakecoin-server-full-code.py
python snakecoin-server-full-code.py
```
![image](https://github.com/user-attachments/assets/5315557d-99d1-44d7-812d-c58aaad2aae8)

Then on the 2nd terminal I ran and opened http://127.0.0.1:5000/blocks to see the blockchain so far,
```
cd ~/iot/lesson10
curl http://127.0.0.1:5000/mine
```
![image](https://github.com/user-attachments/assets/5e081967-9659-4792-8c15-4842a7d5cd8e)
![image](https://github.com/user-attachments/assets/6d31b8b5-e413-4262-948e-eeaf8ac08641)

### Part 4: Python Blockchain App

 I opened 2 terminals yet again. In the 1st terminal, I entered the code:
```
cd ~/iot/lesson10
git clone https://github.com/satwikkansal/python_blockchain_app.git
cd python_blockchain_app
notepad node_server.py // WHERE I EDITED # app.run(debug=True, port=8000) TO app.run(debug=True, port=8000)
python node_server.py
```
In the other terminal, the run_app.py terminal, I entered the code:
```
cd "C:\Users\George Redfern\iot\lesson10\python_blockchain_app"
python run_app.py
```
I had to Resync to fix the server, and clicked request to mine to mine. 
Result of Mine:
![image](https://github.com/user-attachments/assets/ba29d1ec-592c-4721-92bb-650210ede21e)
Additional Images:
![image](https://github.com/user-attachments/assets/f4ec5e96-5763-4cfc-8099-1c7e97130b1c)
![image](https://github.com/user-attachments/assets/3f5b8cb8-7ad5-4f3a-bd58-b71d55f8bbe7)
![image](https://github.com/user-attachments/assets/2313da8f-c948-42f9-964b-2d5a9df2d4b6)

## Summary
During this lab, I faced several issues while setting up the blockchain application. Initially, I encountered a 404 error when trying to post new transactions because the /new_transaction route was not properly defined in node_server.py. I fixed this by ensuring the route was correctly implemented to handle POST requests. Additionally, the frontend was not sending data properly to the backend, resulting in failed transaction submissions. I resolved this by reviewing the request handling in run_app.py, ensuring it packaged the transaction data correctly and sent it to the server with the correct URL. These steps allowed me to successfully run the blockchain app and interact with it.

I pledge my honor that I have abided by the Stevens Honor System- George Redfern
