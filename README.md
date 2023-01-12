# VOICE-BASED-EMAIL-SYSTEM-FOR-VISUALLY-IMPAIRED


## Project Description:

&emsp;&emsp;&emsp;&emsp;Current mailing platforms do not offer voice assistance which creates a void by not allowing a number of people to send mails.
        The requirement for this project has arisen due to the increasing automation of a number of day-to-day activities and lack of a
        voice-controlled mailing facilities. A number of elements such as making a simple call or text has now become just a few clicks
        away, but the mail system has not been automated yet, although it is used extensively by all corporate companies, several 
        international organizations and individuals.
        
        
&emsp;&emsp;&emsp;&emsp;The main focus of the project is an insight on how automation can be useful to save time and data usage the idea enforces the 
        use of a simple GUI (Graphical User Interface) into a mail login web-page. A lot of time is consumed on typing the mail ID, 
        password, verifying the credentials etc. Rather, a predefined email ID and your password can send mails without any delay. 
        The project focuses mainly on minimizing time taken, to type, process requests and revolutionize the process of sending mails.
        
## System Architecture:
&emsp;&emsp;&emsp;&emsp;  - **Processor Type:** Intel(R) Core (TM) i5-9750H

&emsp;&emsp;&emsp;&emsp;  - **CPU Frequency:** 2.60GHz

&emsp;&emsp;&emsp;&emsp;  - **Memory:** 8GB

## System Requirements:

- Python to be installed

- **Required Python Libraries:** 
                           
                           * speech_recognition                             
                           * smtplib                             
                           * bs4                             
                           * imaplib                             
                           * gtts                             
                           * pyglet                           
                           * os                             
                           * time                             
                           * tkinter

## Overall Architecture

&emsp;&emsp;&emsp;&emsp;The process of sending an email and checking of unseen mails using voice controlled email bot sequentially takes place. The receivers email address is identified by matching the obtained voice input with the predefined keyword. Once the ID exists, the text to speech converter prompts the user to enter the subject and body of the email. The output obtained from each of these operations is stored in temporary variables which are used to feed information to the consolidated mail sending function and reading function.


![image](https://user-images.githubusercontent.com/94666680/212098495-aad3c85d-d1af-447b-88f1-003079b73d7b.png)
