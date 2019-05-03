## <center>VStore: A Data Store for Analytics on Large Videos</center>
### Overview
We present VStore, a data store for supporting fast, resource efficient analytics over large archival videos. 
* VStore manages video ingestion, storage, retrieval, and consumption, and controls video formats along the video data path.
* VStore explores an idea called backward derivation of configuration: 
in the opposite direction along the video data path, VStore passes the video quantity and quality expected by analytics backward to retrieval, to storage, and to ingestion. 
* In this process, VStore automatically derives an optimal set of video formats, optimizing for different resources in a progressive manner.
* In response to queries, VStore selects video formats catering to the executed operators and the target accuracy. 
It streams video data from disks through decoder to operators. 
It runs queries as fast as 362× of video realtime.

### Related Publication
**[EuroSys '19]** 
Tiantu Xu, Luis Materon Botelho, and Felix Xiaozhu Lin. 2019. VStore: A Data Store for Analytics on Large Videos. In Proceedings of the Fourteenth EuroSys Conference 2019 (EuroSys '19). ACM, New York, NY, USA, Article 16, 17 pages. DOI: https://doi.org/10.1145/3302424.3303971

### Source Code
[Download (Will Release Soon)](https://www.google.com)

