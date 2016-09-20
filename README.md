# airplay_receiver
Implement Airplay mirroring 

Airplay Client                          Airplay Server

1.| <--------------fp-setup------------>  |
  |                                       |
2.| <--------------fp-setup------------>  |
  |                                       |
  |                                       |
3.| <--------------SETUP--------------->  |
  |                                       |
4.| <--------------GET /info----------->  |
  |                                       |
5.| <--------------GET_PARAMMETER------>  |
  |                                       |
6 | <--------------SET_PARAMMETER------>  |
  |                                       |
7 | <--------------POST /feedback------>  |  (every 2 seconds 1 time)

 
 streaming data to port 7100
 128bytes headers |	H264 DATA | 128bytes headers | H264 DATA | ...					