FROM selenium/standalone-chrome
CMD echo "now running..."

RUN  sudo apt-get update && sudo apt-get install -y fish git vim python3 curl
RUN  curl -kL https://bootstrap.pypa.io/get-pip.py | sudo python3 && sudo pip install selenium

