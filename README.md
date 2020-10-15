# routine_seiscomp3_to_sac
 - Python funtion based on obspy to extract the multiple-stations binary file, which export from Seiscomp3 Jakarta version.
	- Input:
		- Seiscomp3 mseed file (example: 202008170112.mseed file in main directory); 
		- /info_file/sta.txt: station information; 
		- /info_file/hypo.inf: hypocenter information
		- /RESP_FILE/RESP*** : all response file for specific channel and station.
	- Output: 
		- /output/{datetime}/raw_sac/: raw sac files extracted
		- /output/{datetime}/raw_mseed/: raw mseed files extracted
		- /output/{datetime}/sac_final/: intrument response removed sac files with full station - event added in sac header.
# To use this required
- Anaconda 3 (64 bit version): https://docs.anaconda.com/anaconda/install/
- obspy: https://docs.obspy.org/
- pandas: https://pandas.pydata.org/
- numpy: https://numpy.org/
#
Contact: havinhlong1988@g.ncu.edu.tw if you have trouble!
