![Alt text](https://raw.githubusercontent.com/s-j/goodnews/master/static/screenshot.png)

### Background and explanation:
Full presentation: https://www.slideshare.net/s-j/good-news-135157290

### Application architecture:
![Alt text](https://raw.githubusercontent.com/s-j/goodnews/master/static/arch.png)

### Installation and running instructions:
1. Run: ´pip install -r requirements´.
2. Run: ´python -m spacy download en_core_web_md-2.0.0 --direct´.
3. Download: https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz
4. Run: ´python main.py´.
5. Navigate to http://localhost:5000.
6. For training, copy data from logs to training directory. Run and see jupyter notebooks.
