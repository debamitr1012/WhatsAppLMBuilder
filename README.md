# WhatsAppLMBuilder
## Build a Language Model on Your WhatsApp Chats
```
|-- assets
|   |-- input
|   |   |-- chat.txt
|   |-- output
|   |   |-- contacts.txt
|   |   |-- vocab.txt
|   |   |-- train.pt
|   |   |-- valid.pt
|   |-- models
|   |   |--model.pt
|-- src
|   |-- chat.py
|   |-- model.py
|   |-- preprocess.py
|   |-- train.py
|   |-- utils.py
|-- config.py
|-- run.py
```
```
git clone https://github.com/debamitr1012/WhatsAppLMBuilder.git
cd WhatsAppLMBuilder
pip install -r requirements.txt
```
```
python run.py preprocess
```
```
python run.py train --update
```
```
python run.py chat
```
