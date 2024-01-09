sudo apt-get install python3-venv
python3 -m venv .venv && source .venv/bin/activate

deactivate
rm -r .venv
which python

touch requirements.txt
pip freeze > requirements.txt

pip install -r requirements.txt

sudo apt-get install dos2unix
sudo chmod +x main.py && dos2unix main.py

#!./.venv/bin/python
def main():
    print('teste')
if __name__ == "__main__":
    main()


