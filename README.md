# Unfortunately, using reference managers by different co-authors sometimes results in an anomaly in the reference list.
# Some references may be inserted in two places of the references list with the exactly same format or with a bit difference in the data.
# Although reference managers have built-in duplicate removers, when two or more co-authors are working on a manuscript, facing this problem seems inevitable.
# Purpose of this program is to assist authors, especially corresponding authors, to detect duplicate references in the lengthy reference list of manuscripts before submission to a journal.
# You can remove the 100% match duplicates with no further consideration. However, those which are found similar might be duplicate due to different information entry in the reference managers or different due to, for e.g., similar titles of similar author list.
# Therefore, in the case of susceptible duplicates remove them manually after a thorough check. I used FuzzyWuzzy library of Python to find similarities. 
# You can decrease similarity % if you think there is more chance to find duplicates in your references list due to errors in references information entry in the reference managers.

# To use this program, you need to simply copy-past the references list it into the notepad and save it as "references.txt".
# This program is compatible with most references list. However, with some references list format a bit change in the codes may be required.
# Please leave me a comment if you enjoy it or you find a glitch with some references list, or you come up with some hints to change the code. Please mention your selected similarity % in your comment.

# Note: Finding duplicates using duplicated() and removing them with drop_duplicates() methods seems to be ineffective sometime that is why I didnt use them here. 

# This program has been developed by M. Mahdavian.
# https://www.linkedin.com/in/mohammad-mahdavian-50827b53
