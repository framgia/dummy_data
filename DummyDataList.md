#To every Japanese engineer!  This is the dummy data list (for test use) being published currently!
***
 * Source : http://www.find-job.net/startup/dummy-2013
 * Translated by : Framgia Vietnam
 * Translator : Phan Hoang Minh
***

This is the dummy data list that can be used for creating samples and web service. **Dummy URL, IP address, client information, credit card number...**  are all written here. 

All you have to do is referring this document. I think it cover all you need for test!

***
##Credit card numbers
###Visa (16 digits)
* 4111111111111111   
* 4242424242424242   
* 4012888888881881   

Security number : any 3-digit number

###Visa (13 digits, currently not usually used)
* 4222222222222 

Security number : any 3-digit number

###Master Card (16 digits)
* 5555555555554444 
* 5105105105105100 
* 5431111111111111 
* 5111111111111118 

Security number : any 3-digit number

###JCB (16 digits)
* 3530111333300000 
* 3566002020360505 

Security number : any 3-digit number

###American Express (15 digits)
* 378282246310005 
* 371449635398431 
* 341111111111111 
* 378734493671000 (for organization, corporation use) 

Security number : any 4-digit number

###Diners Club (14 digits)
* 30569309025904 
* 38520000023237 

Security number : any 3-digit number

###Discover Card (16 digits)
* 6111111111111116 
* 6011111111111117 
* 6011000990139424 
* 6011601160116611 

Security number : any 3-digit number

###UATP (15 digits)
* 1354 1234 5678 911 

###Paypal
* Test account can be created on https://www.paypal.jp/jp/contents/support/introduction/sandbox/ 

###Credit card number that will return particular error
* 4000000000000010 (fail to check address and postal code)
* 4000000000000028 (fail to check address) 
* 4000000000000036 (fail to check postal code) 
* 4000000000000101 (fail to check security number) 
* 4000000000000341 (request is received but fail to claim) 
* 4000000000000002 (authentication is always rejected & return rejection code) 
* 4000000000000127 (authentication is rejected & return mismatched security number error) 
* 4000000000000069 (authentication is rejected & return time expired error) 
* 4000000000000119 (authentication is rejected & return cannot process error)  
***
##Debit card numbers
###Maestro  (International card)
* 5033 9619 8909 17 
* 5868 2416 0825 5333 38 

###Maestro (UK only)
* 6759 4111 0000 0008 (Issue No. is not required)
* 6759 5600 4500 5727 054 (1-digit Issue No. is required)
* 5641 8211 1116 6669 (2-digit Issue No. is required)

###Maestro  (UK only, 18 digits)
* 6759 0000 0000 0000 00 

###Maestro (UK only, 19 digits)
* 6759 0000 0000 0000 000 

###Solo
* 6334 5898 9800 0001 (Issue No. is not required)
* 6767 8200 9988 0077 06 (1-digit Issue No. is required)
* 6334 9711 1111 1114 (2-digit Issue No. is required)

###Laser (19 digits)
* 6304985028090561515

***
##Dummy URL
###Top level domains
* .test (for testing) 
* .example (for samples) 
* .invalid  (show “invalid” clearly) 
* .localhost (loopback address) 
* .テスト (Japanese)
* .测试 (Chinese simple type) 
* .測試 (Chinese traditional type)
* .δοκιμή (Greek) 
* .परीक्षा (Hindi)
* .테스트 (Korean) 
* .испытание (Russian) 

※ Based on RFC 6761、ICANN document
※ All top level domains can be used as these examples : http://hoge.test/、http://ほげ.テスト

###Second level domains
* http://example.com/ 
* http://example.org/ 
* http://example.net/ 

※ Based on RFC 6761 document
※ Second level domains can be used as this example : http://hoge.example.com/

###Second level domains (Japan)
* http://example.jp 
* http://example.co.jp 
* http://example.ne.jp 

※ Based on JPRS document   
※ Adding 0 ~9 digits after example is also possible (in case of jp, co.jp, ne.jp). For examples : example1.jp, example2.co.jp, example3.ne.jp 
###Second level domain (Japanese domain)
* http://ドメイン名例.jp (meaning: domain name sample)      

※ Based on JPRS document  
※ For japanese domains like .テスト, punycode notation can also be used. For examples : ドメイン名例.jp → xn—eckwd4c7cu47r2wf.jp

***
##Dummy mail address
* hoge@example.com 

***
##Dummy IP address
###IPv4
* 192.0.2.0/24 
* 198.51.100.0/24 
* 203.0.113.0/24 
* 198.18.0.0/15 (for testing benchmark) 

###IPv6
* 2001:db8::/32 

※ Based on RFC 6890 document

***
##Dummy client information
* You can export up to 500 client information records by using http://kazina.com/dummy/ 

###Output form
* HTML, XML, CSV, tab-divided txt

###Output information
* Name, furigana, mail address, gender, age, birthday, married or not, blood type, province, phone number, cell phone number, job, curry eating style (for reference column)

***
##Dummy images
Using reference such as <img src ="http://dummyimage.com/570×295">

###DummyImage.com
  
http://dummyimage.com/570×150

1
<img src="http://dummyimage.com/570x90">

###PlaceIMG
  
http://placeimg.com/570/90/any

1
<img src="http://placeimg.com/570/90/any">

###placehold.jp
  
http://placehold.jp/570×150

1
<img src="http://placehold.jp/570x90.png">
***

Was it good enough? Please tell us on Facebook if you think there is other dummy data that should be published. 
  
I hope you have a good test!
