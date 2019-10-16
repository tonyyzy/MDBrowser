# MDBrowser

MDBrowser aims to let users view molecular dynamics simulation trajectories in the broswer, without storing the trajectory files locally. This project is inspired by [MDSrv](https://github.com/arose/mdsrv/tree/v0.3.5) and UCSD Genome Browser, especially the BigWig format (https://genome.ucsc.edu/goldenPath/help/bigWig.html).

As we are moving towards an Open Science era, computational scientists increasingly publish their datasets with data repositories, such as [Figshare](https://figshare.com/) and [Zenodo](https://zenodo.org/). Most of these repositories utilise cloud storage services as object-storage backend. Making data available is a giant step but making data accessible and easily explorable are equally important. I want to explore the possibility of using purely client-side modern web technology to 'stream' MD trajectories from a variety of web accessible storage options (S3, GCS, ftp).
