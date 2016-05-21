polly
=====

A second cousin to [Textymous](https://github.com/trmml/Textymous), using Twitter DMs as well.

The concept behind polly is ease of messaging, and assimilating Twitter DMs with SMS. DM a certain account with two pieces of information (recipient phone number and body) and the bot will text the body to the provided number.

# Outline

1. Twitter DM (reipient (cell #) and body)
	```
	to: 4251454567
	body: hey! how are you
	```
2. User receives body from TextBelt number
3. To text back 

# Development

Clone, install dependencies, run.


```bash
git clone https://github.com/dabs4dads/polly

cd polly && pip install -r requirements.txt
python main.py # http://localhost:5000
```

# LICENSE
[MIT](LICENSE).