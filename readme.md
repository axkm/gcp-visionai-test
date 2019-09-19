# GCP Vision AI Test

Tutorial used to make this project: https://cloud.google.com/vision/docs/quickstart-client-libraries

## Running This Project

### Requirements

- Python 3 installed
- [GCP Cloud Vision API enabled and a project owner service account key set as the GOOGLE_APPLICATION_CREDENTIALS environment variable](https://cloud.google.com/vision/docs/quickstart-client-libraries#before-you-begin)

### Create and Enter the Virtual Environment

`$ cd /project/directory/`

`$ virtualenv --python python3 env`

`$ source env/bin/activate`

(the virtual environment can be exited using `$ deactivate`)

### Install the dependencies

`$ pip3 install -r requirements.txt`

### Running the project

`$ python3 quickstart.py`

The response should be a list of 10 elements detected from the cat cafe photo found in the resources folder.

## Output for each image

### catcafe.jpg

![cat cafe](resources/catcafe.jpg)

Output:

```
Labels:
Cat
Floor
Interior design
Room
Furniture
Living room
Flooring
Table
Felidae
Small to medium-sized cats
```

### desk.jpg

![desk](resources/desk.jpg)

Output:

```
Labels:
Laptop
Personal computer
Netbook
Electronic device
Technology
Computer keyboard
Computer
Desk
Computer monitor
Space bar
```

### streetconstruction.jpg

![street construction](resources/streetconstruction.jpg)

Output:

```
Labels:
Asphalt
Lane
Road
Road surface
Transport
Traffic
Vehicle
Line
Street
Infrastructure
```
