# airplay_receiver
Implement Airplay mirroring <br />

Airplay Client                          Airplay Server<br />
<br />
1.| <--------------fp-setup------------>  |<br />
  |                                       |<br />
2.| <--------------fp-setup------------>  |<br />
  |                                       |<br />
  |                                       |<br />
3.| <--------------SETUP--------------->  |<br />
  |                                       |<br />
4.| <--------------GET /info----------->  |<br />
  |                                       |<br />
5.| <--------------GET_PARAMMETER------>  |<br />
  |                                       |<br />
6 | <--------------SET_PARAMMETER------>  |<br />
  |                                       |<br />
7 | <--------------POST /feedback------>  |  (every 2 seconds)<br />
<br />
 <br />
 streaming data to port 7100<br />
 128bytes headers |	H264 DATA | 128bytes headers | H264 DATA | ...	<br />
 				
