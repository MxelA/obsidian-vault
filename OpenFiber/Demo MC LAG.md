1. **SCENARIO MC LAG in COLLECT**

	collect (in input we can have or interface or bundle ID)
	MIH_2-N-NPE-01 interface 0/0/0/22  
	
	delivery
	MI_16-E-NPE-01 0/2/0/1
	
	 svlan 121
	 kit WAV_MI_001


2. **SCENARIO MC LAG DELIVERY:**

	collect (in input we can have or interface or bundle ID)
	PE_01-N-NPE-01 interface 0/0/0/12  
	
	delivery
	RM_01-N-NPE-01 0/0/0/24
	
	 svlan 208
	 kit PIT_RM_001

3. **SCENARIO MC LAG COLLECT + MC-LAG DELIVERY** // This is not valid scenario collect router not xconnect it is vifi so we not run discovery collect MC-LAG
		Collect: 
			ME_01-N-NPE-03 interface 0/0/0/11 
		Delivery
			PA_04-N-NPE-01 0/0/0/15
			PA_04-N-NPE-02 0/0/0/9
		SVlan
			681
		Kit
			SKYPA02/01