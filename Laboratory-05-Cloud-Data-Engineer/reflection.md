
# Mission Reflection

This laboratory activity helped me understand why object storage is commonly
used for cloud applications that manage large amounts of unstructured data.
Object storage is well suited for millions of photos because each image can
be stored as an object together with metadata and an identifier. Unlike a
traditional hard drive that is attached to a particular computer, object
storage is designed to provide access to large collections of files through
cloud services and APIs. This makes it useful for applications that need to
store many images and other media files.

Docker made deploying MinIO easier because I did not need to manually install
and configure every component of the storage server. I was able to use one
Docker command to download the MinIO image, create the container, configure
the login credentials, and expose the required ports. The container also
made the deployment easier to reproduce in another environment.

A bucket is a logical container used to organize objects in object storage.
In this activity, I created a bucket named `client-photos` and uploaded a
sample file into it. The bucket provided a simple way to organize the files
for the client's photo-sharing application.

Large enterprise companies can use several methods to reduce the risk of
data loss when physical hardware fails. These can include replication,
redundant storage systems, backups, and distributing data across different
servers or locations. These methods help ensure that a hardware failure does
not result in the permanent loss of important data.

My confidence with the Linux command line is also improving. At the beginning
of the activity, some Docker commands were unfamiliar to me. After running
commands such as `docker ps` and using Docker to deploy MinIO, I became more
comfortable working with the terminal. I learned that carefully reading the
command and checking the output makes command-line tasks easier to understand.
