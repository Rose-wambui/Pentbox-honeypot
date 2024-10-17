# Pentbox-honeypot
# Setting up Honeypot using pent-box
PentBox is a tool that allows us to create honey-pot in our system. This is written in ruby language.

# How to Download and Install Pent-box on Kali Linux.
We will use the following command in kali Linux to clone it from GitHub.

git clone https://github.com/technicaldada/pentbox

![image](https://github.com/user-attachments/assets/c496466c-aa7d-43ea-b451-7b420db8e334)

Then change directory to where PentBox has been downloaded.
cd pentbox

![image](https://github.com/user-attachments/assets/a866f88a-40b3-4b07-bc0d-ef4504d4f175)

We need to unzip the file since its zipped using the following command.

tar -zxvf pentbox.tar.gz

![image](https://github.com/user-attachments/assets/b2ee84d7-4b93-4cdf-a036-c45fdeeff496)

Changing directory again to the file we just unzipped.

cd pentbox-1.8

![image](https://github.com/user-attachments/assets/e8bdc791-3b84-4e85-a66a-21fde7a203d9)
This directory contains all the files above.

# Setting up the honeypot with pentbox
To run and start the pentbox, we will use the following command.

./pentbox.rb

![image](https://github.com/user-attachments/assets/e3f1e31f-e1d3-4b91-890f-45ac86852c1e)

We will select the Network tools section from the Pentbox menu by typing: 2

Next menu we will select option 3, web.

To select the Fast Auto Configuration option, on the run Pentbox screen, type: 1

You will get a notification that the HONEYPOT ACTIVATED ON PORT 80.

![image](https://github.com/user-attachments/assets/d110f4b7-3791-4845-a624-d97f02e6c978)

# Testing Honeypot Fast Auto Configuration Functionality
We are going to get the IP address of our kali Linux machine using ifconfig

Pasting the address in out browser we get the following error

![image](https://github.com/user-attachments/assets/dc6a6659-6bc2-4b35-9b14-4e0aa5d51d10)

On our kali terminal the following is generated;

![image](https://github.com/user-attachments/assets/67a42f04-9e9a-4184-b9a4-7c06f413278b)
