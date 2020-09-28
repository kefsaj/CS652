# Google vs Facebook DCN
 
This is a comparision of Google Data Center Network and Facebook Data Center Network topologies. 

|Facebook	| Jupiter |
|--|--|
| Main goal is train small teams of efficient operators to manage intrastructure| Main goal is to develope tools which target specific for the particular eqickments 
|-Small sever pods which are highly scaleable | Manufacture simple and easily deploiable clusters which have minimal software to use (Jupitar Rising, P12) |
| BGP4 routing protocol| BPG Stack
| Focused on delievering a quick and simple front end directed toward each end user|Local CLI to manage and recieve switch status  
| Runs the four-post architechure | Runs the Firepath Master Redundancy Protocol
|Modeled as an end-to-end non-oversubscription environment| Watchtower is enabled to support depopulated deployment.|
 

 - Facebook DNC is imited by the port density of the cluster switch
 
 
### Control Plane
|Facebook	| Jupiter |
|--|--|
|Custom designed microservers called MiniLake|Managed by a route controller which collects information and notifyies each switch

## References: 
### Jupiter Rising: A Decade of Clos Topologies and Centralized Control in Google’s Datacenter Network
https://research.google/pubs/pub43837/
### Introducing data center fabric, the next-generation Facebook data center network
https://engineering.fb.com/production-engineering/introducing-data-center-fabric-the-next-generation-facebook-data-center-network/
