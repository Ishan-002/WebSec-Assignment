# WebSec-Assignment
Solution of the Web Security assignment



# Problem-1   
https://backdoor.sdslabs.co/challenges/BRWSR


Open network conditions in developer tools, change the user agent to custom and then change it to SDSLabs.You'll see the flag.  
FLAG: e77aec24943bb31c63547812d1130c67d0e7e941bf5d85bfef0492cc68050aef


# Problem-2
https://backdoor.sdslabs.co/challenges/WHAT-IP  


As given by the hint, the webpage should be opened with our localhost i.e with the IP address 127.0.0.1. So, I used the command  curl --header "X-Forwarded-For: 127.0.0.1" http://hack.bckdr.in:16003/index.php  
It allowed me access to the page and the flag came.  
FLAG: d025c4ca8e71501df3581d995c9d838801125d16b0468f6b980969d476b2ac55


# Problem-3
https://2019shell1.picoctf.com/problem/12284/


Here login occurs for any username and password supplied but to the page where the flag is not present. So, this means that the admin could posssibly be the one who can access the flag. For this I used the 'EditThisCookie' extension in chrome to edit the cookie named admin which was set to false and changed it to true. The flag came up after reloading the page with the modified cookie content.  
FLAG: picoCTF{th3_c0nsp1r4cy_l1v3s_6f2c20e9}


# Problem-4
https://2019shell1.picoctf.com/problem/12255/


This problem is same as problem-1. Here the similar procedure is to be repeated, the only difference being, picobrowser to be written instead of SDSLabs.
