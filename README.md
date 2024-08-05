# Cowin-Vaccine-Notifier
Python Web-Scapper for scrapping vaccination slots from cowin.gov.in website.

Developed a notifier which notifies if a vaccine is available on provided pincode. If the slots free to book it will send a notifier mail to registered e-mail. 
At the time of covid-19 it is very difficult to search for vaccines as everywhere a vaccination drive is going on. 

Through this python script, by just providing e-mail it will automatically fetch current data from co-win site and checks if the vaccine is available on particular center, it will fetch all the details of the vaccine and sends data return to the python scripts. 

# How it works :
1. Make some changes in the code add your mail id and password for sending mail through python script(at SENDER and PASSWORD in code) and for receiving mail(at RECIPIENT).
2. Run the pyhton script it will promt for pincode, enter it.
3. Web scrapping is done cowin.gov.in and if the vaccination slots are available on the provided pincode it will display all the details and send a mail on registered mail.

# Output :
![op1](https://github.com/arbaj2002/Cowin-Notifier/assets/57356090/54d39d71-a5a4-435e-8011-d6ba37b5b70f)
![op2](https://github.com/arbaj2002/Cowin-Notifier/assets/57356090/60e24a42-3e2b-42ec-b675-9d5b11bdd38e)
