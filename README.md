# project-chatbot-rasa
โปรเจคแชทบอท นศ DSBA KMITL 62070266&amp;62070267

### Requirements:
-rasa 3.x </br>
-tensorflow </br>
-ujson

## How to run nlu server to parse text

1) rasa run --enable-api -m models/nlu-20220305-220638-purple-bassoon.tar.gz
2) send *POST* request to http://localhost:5005/model/parse in **JSON** format
</br></br>
Examples:</br>
![image](https://user-images.githubusercontent.com/54878524/156889864-5ba8b350-f957-4e21-8ae0-23a4574aff0a.png)</br>
Response:</br>
![image](https://user-images.githubusercontent.com/54878524/156889907-6e68ab80-8268-49f4-8fa6-89237f9e4430.png)
