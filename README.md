
# Indian Sign Language Detection using Yolo v5

Hand gestures are an important part of nonverbal communication and form an integral part of our interactions with the environment. Notably, sign language is a set of hand gestures that is valuable to millions of disabled people.However, deaf/dumb users experience difficulty in communicating with the outside world as most neither understand nor can use sign language. Gesture recognition and classification platforms can aid in translating the gestures to those who do not understand sign language.

Indian Sign Language (ISL) is used in the deaf community all over India. 

## Installation

Clone Yolov5 and install the requirements

```bash
git clone https://github.com/BiJu-02/ISL-Yolov5  
cd yolov5
pip install -r requirements.txt  
```
    
## Deployment

To run this project

Move the detectISL.py file into the yolov5 directory and run the following command by opening terminal inside that directory.

```bash
py detect.py --weights best.pt --source 0
```

