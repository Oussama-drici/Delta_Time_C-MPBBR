The balance congestion goal is defined by loading the data to the less congested path
instead the high congested path to minimize delay and the loss of packets, from the ML
research in laboratory by Mr. KHELOUFI Anis, Mr. EL-HASSAR Sidahmed Reda, they
found that the high infuencable variable in the detection of congestion is Delta time or
the time between the packets, this Delta time helps us to predict if there is a congestion
or not, in our amelioration we tried to include this Delta time to detect congestion in the
path in order to achieve the balance congestion goal, the amelioration is based on the new
proposed New_Rtt_BBRv1 in TCP.

#Instructions:

How to Run:

Just compile and install is as a module. Change the default Congestion Algorithm to "DT_C-MPBBR"

Above development was based on the MPTCP v0.95.0 deployed in Linux kernel version of v4.19.206 


Regards,

Computer Systems Enginner Drici Oussama.

For any information contact me at o.drici@esi-sba.dz
