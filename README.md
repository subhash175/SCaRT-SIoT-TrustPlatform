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

pack_f Count: Number of packets forwarded at a given time instance betweeen a trustor and trustee

pack_d Count: Number of packets dropped at a given time instance betweeen a trustor and trustee

pdr: Packet Delivery ratio in the range {0,1}

frds: Whether a trustor and a trustee are friends or not. 1-> Friends, 0-> Not Friends

coi_id: Community encompassing a trustor and a trustee. 1-> Involved with same community, 0-> Not Involved
