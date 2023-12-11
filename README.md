# General Instructions

  a) Run the accidented_car_model.ipynb to see the model building process
  
      Notebook Instructions
          1) Here is the link to the cleaned and preprocessed datasets used in building the model
                  https://drive.google.com/drive/folders/1N1b10zolyK65KwMK_1yktn5zlYgr9DI8?usp=sharing
          
          2) kindly change all directories to conform with the codebase in this notebook
            data_dir = "/content/drive/My Drive/Curacel_ai_engine/car_data"
            train_dir = "/content/drive/My Drive/Curacel_ai_engine/car_data/train"
            val_dir = "/content/drive/My Drive/Curacel_ai_engine/car_data/val"

         3) Remember:
            Accidented car = a_car
            Non_Accidented car = n_car


b) when you get model.pth output from above, copy it into the folder here -> Curacel-tasks/car_detection_api/ml_model/ 

c) Use the inference api at https://github.com/Engrgit/vehicle_detector/tree/main/car_detection_api for testing  

d) Run the car detector API by installing dependencies in requirements.txt

e) Run app.py to load the Flask web API

f) Have a lovely day and enjoy tesing the model.


