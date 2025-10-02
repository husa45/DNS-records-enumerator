# DNS-records enumerator 
This is a DNS records enumerator , written in python
you can use it to enumerate all known DNS records .

## installation

**1.create a python virutal environment , to avoid dependency conflicts**

>python3 -m venv  $(name_of_you_environment)


**2.activate your virtual environment by typing : **

>source $(name_of_env)/bin/activate
>


**3.clone the repository to your virtual environment , to do so , type :**

>git clone https://github.com/husa45/DNS-records-enumerator
>


**4.install all the dependencies int the requirements.txt file:**

>pip3 install -r requirements.txt


**5.Use the script by running :**

>python3 dns_dig.py  --type={A,AAAA,MX,.....}     domain_name1   domain_name2  .... { Domain names to query }
>


**enjoy !!!!**
