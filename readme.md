python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

python attack-to-elk.py




Config ayarları için

attack-to-elk.py içerisinde 7 ve 8. satırlardaki elastic search bilgisi düzenlenmelidir.

es_host = "127.0.0.1"

es_port = "9200"


