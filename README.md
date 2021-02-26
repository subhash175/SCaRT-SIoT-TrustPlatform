# SCaRT-SIoT-TrustPlatform

SCaRT-SIoT: Towards a Scalable and Robust Trust Platform for Social Internet of Things

The current dataset is the sample dataset, we will update the full dataset soon.

This data set contains following columns as feature. 

csv: Time_instances;src;dst;pack_f;pack_d;pack_f Count;pack_d Count;pdr;frds;coi_id;

Time instance: Each time instance is the 5 seconds interval

src: Source id as Trustor

dst: Destination id as Trustee

pack_f: Packet forwarded. 0->Not Forwarded, 1-> Forwarded

pack_d: Packet dropped. 0->Not Dropped, 1-> Dropped

pdr: Packet Delivery ratio in the range {0,1}

frds: Whether a trustor and a trustee are friends or not. 1-> Friends, 0-> Not Friends

coi_id: Community encompassing a trustor and a trustee. 1-> Involved with same community, 0-> Not Involved

Please cite the following two papers to use this dataset. Thanks.

1) Subhash Sagar, Adnan Mahmood, Quan Z. Sheng, and Sarah Ali Siddiqui. 2020. SCaRT-SIoT: towards a scalable and robust trust platform for social internet of things: demo abstract. In Proceedings of the 18th Conference on Embedded Networked Sensor Systems, Association for Computing Machinery, New York, NY, USA, 635–636. DOI:https://doi.org/10.1145/3384419.3430434

2) @misc{sagar2021machine,
      title={Towards a Machine Learning-driven Trust Evaluation Model for Social Internet of Things: A Time-aware Approach}, 
      author={Subhash Sagar and Adnan Mahmood and Quan Z. Sheng and Munazza Zaib and Wei Emma Zhang},
      year={2021},
      eprint={2102.10998},
      archivePrefix={arXiv},
      primaryClass={cs.CR}
} 
