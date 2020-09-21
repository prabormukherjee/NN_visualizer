# NN_visualizer

Here I implemented a Neural Network model visualizer, using `Flask` and `Streamlit`. I trained a machine learning model using tensorflow on the mnist dataset of hand digit recognition on 20 epochs. The I saved the model with `.h5` format. The python file will take care of the server and prediction.      

All the source code is provided here. The notebook will train the model and save `model.h5` (which  is also added). The `ml_server` will start the server using flask and `app.py` will customise the page with streamlit and plot the result.    

### Instruction to run     
+ open cmd
+ cd over the `NN_visualizer`
+ run the command `python3 ml_server.py`
+ it will start the flask server in `http://127.0.0.1:5000/`    
+ run the command `streamlit run app.py`    
+ check the `http://localhost:8501`, where the streamlit is running
