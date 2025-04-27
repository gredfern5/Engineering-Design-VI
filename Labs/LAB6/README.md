# Lab 6 | Node.js and Pystache
## George Redfern
### Lab Instructions:
  Go to the GitHub repository Lesson 6; Install Node.js and run hello-world.js, hello.js, and http.js; Refresh the webpage to see server activities; Install Pystache and run say_hello.py that uses the template in say_hello.mustache

  ### Part 1: Node.js

  I installed Node.js and added it to the path. 

- I navigated to the **lesson6** directory:
  ```bash
  cd ~/iot/lesson6
  ```
- I ran the **hello-world.js** file with Node.js:
  ```bash
  node hello-world.js
  ```
- The server was now running at **http://127.0.0.1:3000/**.
![image](https://github.com/user-attachments/assets/f0fbe584-0cab-4be9-b342-55be27131a57)
- I ran the **hello.js** file with Node.js:
  ```bash
  node hello-world.js
  ```
- The server was now running at **http://127.0.0.1:8080/**.
![image](https://github.com/user-attachments/assets/b2f10527-951c-4232-9ab7-5dba44bee906)

- http.js says how many times the page has been forged

 ### Part 2: Pystache

---

- I installed Pystache by running:
  ```bash
  pip install pystache
  ```
- I navigated to the `lesson6` directory:
  ```bash
  cd ~/iot/lesson6
  ```
- I verified the contents of the template file `say_hello.mustache`, which included:
  ```
  Hello, {{to}}!
  ```
- I reviewed the `say_hello.py` script, which:
  - Rendered a simple message: "Hi Alexa!"
  - Used a `SayHello` class to insert "World" into the template.
  - Parsed and rendered a pre-parsed template with dynamic data ("Google" and "Siri").
- I ran the script:
  ```bash
  python say_hello.py
  ```
- The output was successful:
  ```
  Hi Alexa!
  Hello, World!
  Hey Google!
  Hey Siri!
  ```
![image](https://github.com/user-attachments/assets/5cd1ecd4-a420-4fa6-971b-47314c803efd)

---

# Summary
In this lab, I learned how to use Pystache templates in Python to dynamically generate text by rendering variables into predefined formats.

I pledge my honor that I have abided by the Stevens Honor System- George Redfern

