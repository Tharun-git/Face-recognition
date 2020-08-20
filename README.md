# Face-recognition
Face recognition model using CNN in both Keras and Tensorflow <br />
Run save_face.py to save your faces in database. <br />
   It will ask for id. start from 1.<br />
   image number starts from 1 and it takes 300 images of each face to train.<br />
Run store_facial_features.py<br />
   It converts each face into embeddings and store in dataset.csv where each row contains 128 columns<br />
Run csv_to_pickle.py <br />
  Four new files will get generated (train_features, test_features,train_labels and test_labels).<br />
Run python train_model_tf.py<br />
Run python train_model_keras.py<br />
python recognize.py<br />
