
# Storage Types Research

Cloud storage can be divided into three common types: Block Storage,
File Storage, and Object Storage.

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data as individual blocks that can be attached to a server and formatted with a file system. | Virtual machines, databases, and applications that require low-latency storage. | AWS EBS |
| File Storage | Stores data in files and folders using a shared file system that multiple systems can access. | Shared documents, application files, and network file systems. | AWS EFS |
| Object Storage | Stores data as objects together with metadata and a unique identifier inside containers called buckets. | Photos, videos, backups, documents, and other unstructured data. | AWS S3 |

## Why Object Storage?

Object Storage is suitable for the client's photo-sharing application because
it is designed for large amounts of unstructured data such as images. It also
allows files to be organized into buckets and accessed through web or API
interfaces.
