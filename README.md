# MinioClient

CRUD operations for Minio Datbase <a href= "https://min.io/"> Minio </a>

```
Requirements:

minio
pandas
pickle

Minio client installation:  pip install minio
```

```
Data format supports:
1.CSV
2.Pickle
```

```
Currently supports Create, Read and Delete Operations

endpoint

1.  get_data : read data from the database by passing {bucket_name, object_name, type="pkl"}

2. insert_data: insert data into the database by passing {data, bucket_name, object_name, toCreateNewBucket=False}

   data is DataFrame object or Pickle format object data..

3. delete_model: delete object from the database by passing {bucket_name, object_name}
```
