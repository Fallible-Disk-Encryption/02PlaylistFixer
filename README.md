**02PlaylistFixer**  
A little collection of information regarding the AGPTEK A02 and how it handles playlists.  
  
**TO-DO:**  
[ ] Re-create the Playlists  
		Maybe ask interactively if they needed to be sorted by Newest First? If Y, then TAC  
[ ] Delete original Files?  
[ ] Instead of CATing a giant amount of lines, place into text file first?  
		Might be an issue for people with tens of thousands of episodes.  
  
**Extra**  
Makes a copy of each file for backup purposes :)  
  
for f in *; do cp "$f" "$f.BKP"; done
