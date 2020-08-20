# Face-recognition
Face recognition model using CNN in both Keras and Tensorflow <br />
1. Run save_face.py to save your faces in database. <br />
   a. It will ask for id. start from 1.<br />
   b. image number starts from 1 and it takes 300 images of each face to train.<br />
2. Run store_facial_features.py<br />
   a. It converts each face into embeddings and store in dataset.csv where each row contains 128 columns<br />
3. Run csv_to_pickle.py <br />
   a. Four new files will get generated (train_features, test_features,train_labels and test_labels).<br />
4. Run python train_model_tf.py<br />
5. Run python train_model_keras.py<br />
6. python recognize.py<br />
