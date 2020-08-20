# Face-recognition
Face recognition model using CNN in both Keras and Tensorflow \n
Run save_face.py to save your faces in database. 
   It will ask for id. start from 1.
   image number starts from 1 and it takes 300 images of each face to train.
Run store_facial_features.py
   It converts each face into embeddings and store in dataset.csv where each row contains 128 columns
Run csv_to_pickle.py 
  Four new files will get generated (train_features, test_features,train_labels and test_labels).
Run python train_model_tf.py
Run python train_model_keras.py
python recognize.py
