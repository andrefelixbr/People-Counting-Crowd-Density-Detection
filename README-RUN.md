#Configure Python Virtual Env


Install Python Virtual Env

	python3 -m venv env


Creating a Virtual Env

	virtualenv venv


Using Virtual Env

    source venv/bin/activate


* Installing required libraries

  pip install -r requirements.txt


* Testing

	python people_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --input videos/example_01.mp4 --output output/example_01_output.mp4


