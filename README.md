## Hi there 👋

I am a Data Science Immersive graduate from General Assembly Singapore and new to the data community! Coming from a Hospitality background, this has been quite a major shift in my career trajectory, but I've been fully enjoying my time picking up new skills like Python and SQL as I navigate my way thorugh these uncharted waters.

<a href="https://www.linkedin.com/in/shawn-sing/" target="_blank" rel="noopener noreferrer"><img src="./linkedin_original.svg" alt="LinkedIn Logo" height="18"/></a> Happy to connect on LinkedIn, and also currently actively looking for my next role. 😉

:camera_flash: Fun fact: I enjoy photography as a hobby, especially while travelling. Check out some of my photos [here](https://eeshawn.tumblr.com) and [there](https://www.flickr.com/photos/ee_shawn/).

---

## :roller_coaster: Data Science Projects
Some projects that I have been working on during my free time.

### :office: [HDB Resale Price Dashboard](https://github.com/eeshawn11/HDB_Resale_Dashboard)

Exploration of data retrieved from [Data.gov.sg](https://data.gov.sg/dataset/resale-flat-prices), in particular HDB resale prices from 2012, to create an interactive dashboard. I am also hopeful that any insights gleaned could be helpful to my own HDB purchase journey, but no fancy prediction model here (yet?), just some charts and maps.

This is an ongoing project to document my learning with using Streamlit and various Python libraries. While such a dashboard could perhaps be more easily created using PowerBI or Tableau, I am also taking the opportunity to explore the various Python plotting libraries and understand their documentation.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://eeshawn-hdb-resale.streamlit.app/)

**Skills Demonstrated:**

- Data extraction through live Data.gov.sg API
- Data transformation with `pandas`
- Working with geospatial data using OneMap [API](https://www.onemap.gov.sg/docs/), `Shapely` and `Mapbox`
- Data visualisation with `Vega-Altair` and `Plotly`
- Web app deployment with `streamlit`

### :electric_plug: [Time Series Forecasting with Prophet](https://github.com/eeshawn11/Time-Series-Forecasting)

Time series forecast using a [dataset](https://www.kaggle.com/datasets/eeshawn/half-hourly-electrical-demand-in-singapore) gathered from the [Energy Market Authority](https://www.ema.gov.sg/index.aspx) of Singapore. The original data is stored in individual weekly Excel files by month and year, which I have scraped from the website and combined into a dataset.

This is a relatively straightforward univariate time series problem involving electricity demand in Singapore and Prophet achieved a Mean Absolute Percentage Error (MAPE) of **3.67%** when predicting for demand in January 2023.

[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/eeshawn/time-series-forecasting-with-prophet)

Skills Demonstrated:

- Extracting data through Web scraping with `Selenium`
- Data transformation with `pandas`
- Loading and storing data into `Kaggle` dataset
- Time series forecast with Facebook `Prophet`

---

## <img src="./general-assembly-space-academy.png" alt="General Assemly Logo" height="20"> [Data Science Immersive Projects](https://github.com/eeshawn11/DSI33-Shawn)
A collection of various projects completed during my 12-week immersive with General Assembly.

**Skills Demonstrated:**

- Supervised machine learning with `scikit-learn`, with a variety of regression, classification and ensemble models
- Natural Language Processing (NLP) techniques with `NLTK`
- Presentation of findings and recommendations at the end of each project
- Collaboration and version control with `git`

### :surfer: [Capstone - Image Caption Generator](https://github.com/eeshawn11/DSI-Capstone)

Capstone project from Data Science Immersive. Trained an image caption generator with attention mechanism that achieved a BLEU-1 score of 0.52 on the [Flickr30k](https://www.kaggle.com/datasets/eeshawn/flickr30k) dataset.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://eeshawn-dsi-capstone.streamlit.app/)

**Skills Demonstrated:**

- Deep learning, computer vision and natural language processing with `TensorFlow` and `Keras`
- Handling of large dataset using TensorFlow's tf.data API
- Deployment of custom Keras model to `streamlit` web app

---

<!--
### [Naruto Hand Seals - Gesture Recognition](https://github.com/eeshawn11/DSI33-Shawn/tree/main/Side_Projects/Naruto_Gesture_Recognition) [WIP]

Training and deploying a machine learning model that can recognise 12 basic hand seals from the Naruto anime using TensorFlow's Object Detection API.

While the model appears to be able to detect and recognise the hand seals that I am making, it also recognises my face as a "rat" seal, so perhaps there's more to be done to overcome this. Next step would also include deploying the model online, so you could also give it a try!

**Skills Demonstrated:**

- Collecting and building my own dataset using `OpenCV` and annotating the collected images with `LabelImg`
- Transfer learning using a pre-trained network with `TensorFlow` Object Detection API
-->
