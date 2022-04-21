# Control-plane-protocol-stack

![](/photos/control_plane_protocol_stack.png)

It supports in carrying the control informations between the user equipment and gNodeB and the core-network.

Each layers shown in above diagram provides the services to the layer above and consumes the services of the below layer.

**Protocols**
1. NAS  -  includes function for Authentication, Security, Idle mode procedure (Paging). It has no relation with Radio Access Network.

2. RRC  - includes function for System Information, Radio Bearer, Measurement Configuration.

3. PDCP - includes function for Header Compensation, Ciphering & Integrity Protection, Duplicate Removal.

4. RLC  - includes function for ARQ, Segmentation.

5. MAC  - includes function for Retransmission, Multi/Demulti-plexing, Scheduling

6. PHY  - includes function for Efficient Wireless Communication.
