# dog-breed-classifier

Data origin: https://www.kaggle.com/datasets/jessicali9530/stanford-dogs-dataset/data

In order to use data in Colab:

1. Download Kaggle API key in json file.
2. Upload this key to Colab:

  from google.colab import files

  files.upload()

3. Configure Kaggle enviroment:

  !mkdir -p ~/.kaggle #Create directory for the key

  !mv kaggle.json ~/.kaggle/ #Move the key

  !chmod 600 ~/.kaggle/kaggle.json #set permissions

4. Install Kaggle Library:

  !pip install kaggle

5. Download the dataset:

  !kaggle datasets download -d jessicali9530/stanford-dogs-dataset -p /content

6. Unzip:

  !unzip -q /content/stanford-dogs-dataset.zip -d /content/stanford-dogs
