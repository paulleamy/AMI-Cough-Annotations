Annotations of the events labelled as cough in the AMI corpus (http://groups.inf.ed.ac.uk/ami/corpus/). List of annotations is currently being revised to include additional detail and more accurate representations of events included here.

Origial paper related to this database can be found at https://ieeexplore.ieee.org/document/8904929

Please use the following citation if reusing this work:

P. Leamy, D. Berry, T. Burke and D. Dorran, "Re-annotation of cough events in the AMI corpus," 2019 30th Irish Signals and Systems Conference (ISSC), Maynooth, Ireland, 2019, pp. 1-5.

@INPROCEEDINGS{8904929, author={P. {Leamy} and D. {Berry} and T. {Burke} and D. {Dorran}}, booktitle={2019 30th Irish Signals and Systems Conference (ISSC)}, title={Re-annotation of cough events in the AMI corpus}, year={2019}, volume={}, number={}, pages={1-5},}

A playback tool is also included, ```listening_tool.html```, which can be used to playback array and headset recordings once the recordings have been unzipped.

Four sets of recordinga are provided here in indiviudal ZIP files:
* ```events_array.zip``` contains table-top array microphone recordings of each event
* ```preview_array.zip``` contains the same table-top array microphone recordings of each event but with aa larger window for more context when previewing sounds
* ```events_headset.zip``` contains the headset mix recordings from each meetin participant
* ```preview_array.zip``` contains the same headset mix recordings of each event but with a larger window for more context when previewing sounds


```Annotations_master.csv``` contains descriptions of each these events with the following headings
* File number: corresponds to the WAV filename	
* Meeting ID: ID used to identify the meeting recording form the AMI corpus	
* Microphone: Not required	
* Speaker ID: ID used to identify speaker from meeting	
* Start: Start time of event in seconds
* End: End time of event in seconds	
* Cough: 1 - cough, 0 - non-cough	
* Volume: Relative volume of cough in recording	
* Type: Type of sound
  * For cough events provides a description of the cough type i.e. dry, moist, hacking, etc.
  * For non-cough events gives a description of the event i.e. throat clear, laugh, etc.
* Background: 1 - background noise overlapping, 0 - non background noise overlapping	
* B. Type: Type of background noise if present	
* B. Volume: Relative volume of background noise	
* Close call: Events that may warrant an additional opinion on the decided values	
* Comments: Addtional comments included here
  * One comment to be aware of is "close to lasrt sound" or "close" which indicates that the previous event is in close proximity to the event with this comment suggesting that these events maybe part of a larger event, for example a volley of coughs or thoat clears.






