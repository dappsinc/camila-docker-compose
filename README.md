# Camila Docker Compose

Camila is a Contract Lifecycle Management (CLM) network for inter-firm process automation. Camila is an open source CorDapp, built on Corda.

```
git clone https://github.com/dappsinc/camila-docker-compose

docker-compose up

```

This will provision a 8 node network and in addition to 1 notary node.

```
	   8 Node Network Graph | 28 Edges | 1 Notary
-------------------------------------------------------------------

	 /--------\   /--------\   /--------\                                   
	|	       | |	        | |          |                  
	|  PartyB  | |  PartyC  | |  PartyD  | 
	|          | |	        | |          |                   
 	 \--------/   \--------/   \--------/

 /--------\	      /--------\	   /--------\
|	       |	 |	        |	  |	         |
|  PartyA  |	 |  Notary  |	  |  PartyE  | 
|	       |	 |	        |	  |	         | 
 \--------/	      \--------/       \--------/

	 /--------\   /--------\   /--------\                                   
	|	       | |	        | |          |                            
	|  PartyH  | |  PartyG  | |  PartyF  | 
	|          | |	        | |          |                             
 	 \--------/   \--------/   \--------/

--------------------------------------------------------------------


```