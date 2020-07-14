# Freedemy

## Contributing
Clone the repo:
``` bash
git clone <url>
```
**Install `yarn` if you don't have it installed already:**
```bash
npm install --global yarn
```
Navigate to the Flask app location:
``` bash
cd freedemy/app
```
Create a venv and activate it:
``` bash
python -m venv venv
source venv/bin/activate
```
On Windows, use following to activate:
``` powershell
.\venv\Scripts\activate
```
From within the app directory, install dependencies:
``` bash
pip install -r requirements.txt
```
#### Run the app
Open two terminals to run React and Flask separately.
On Terminal 1:
``` bash
yarn start
```
On Terminal 2:
```bash
yarn start-app
```
**Note**: venv should be activated when running the app
