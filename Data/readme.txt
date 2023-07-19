1. The file scam_nonscam_all.pkl contains only labeled collusion scam and non-scam. It has the following columns:[ 'Comments', 'youtube_code', 'Comments_likecounts',
'Comment_time', 'Replies', 'Replies_likecounts', 'Replies_time', 'video_published_at', 'rater1', 'rater2', 'IS_SCAM_corrected']
** 'rater1', 'rater2', 'IS_SCAM_corrected' columns contains the labels of a particular comment thread
** 1 indicated collusion scam and 0 indicates no scam

2. The file spams_and_unlabeled.pkl contains all the spam threads and unlabeled threads. The column "label" has that information. Please note, we didnot collect the metadata
for this file
