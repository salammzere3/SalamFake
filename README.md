<h1 align="center">SalamFake</h1>
<p align="center">A simple library project, a library function to make a temporary email, receive all messages</p>


## Installation :
```
pip install SalamFake
```
### Example
```python
# by Salam Hunter
from SalamFake import *

# Show email
mail = Email()
print(mail)

# fetch the message
while True:
	if mail.new_message():
		print(mail.get_message())
```
### The result

```json
[
  {
    "read": false,
    "expanded": false,
    "forwarded": false,
    "repliedTo": false,
    "sentDate": "2021-05-10T07:32:41.000+0000",
    "sentDateFormatted": "May 10, 2021, 7:32:41 AM",
    "sender": "author@example.com",
    "from": "[Ljavax.mail.internet.InternetAddress;@37e8c463",
    "subject": "Test message",
    "bodyPlainText": "",
    "bodyHtmlContent": "mas",
    "bodyPreview": "Test description\r\n",
    "id": "2118940165622869807"
  }
]

```
</p>
<p align="center">
  <img alt="salammzere3' Github Stats" src="https://github-readme-stats.vercel.app/api?username=salammzere3&show_icons=true&include_all_commits=true&hide_border=true" />
 <img src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=salammzere3&hide=ruby,perl&hide_border=true" /> 
</p>

