# super-telegram
{"ok":true,"result":[{"update_id":523349956,
"message":{"message_id":51,"from":{"id":303262877,"first_name":"YourName"},"chat":{"id":303262877,"first_name":
"YourName","type":"private"},"date":1486829360,"text":"Hello"}}]}
/sendMessage?chat_id=303262877&text=test
from bottle import run, post
@post('/')  # our python function based endpoint
def main():  
    return 
if __name__ == '__main__':  
    run(host='localhost', port=8080, debug=True)
{"ok":true,"result":true,"description":"Webhook was set"}
