<img align="left" width="300" height="300" src="https://github.com/Aryanstha/Hawk-Eye/blob/main/logo.png?raw=true">
<h1>Hawk-Eye</h1>

### An OSINT tool to search fast for accounts by username across 153 sites.

</br>



## Setup

#### Clone the repository
```shell
git clone https://github.com/Aryanstha/Hawk-Eye
cd Hawk-Eye
```

#### Install requirements
```shell
pip install -r requirements.txt
```

## Usage

#### Search by username
```python
python hawkeye.py -u username
```
#### Run WebServer
```python
python blackbird.py --web
```
Access [http://127.0.0.1:9797](http://127.0.0.1:9797/) on the browser

#### Read results file
```python
python hawkeye.py -f username.json
```
#### List supported sites
```python
python hawkeye.py --list-sites
```
