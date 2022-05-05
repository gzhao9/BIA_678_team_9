<<<<<<< HEAD
Granularity|Feature|Definition (The comment used does not contain the issue reporter's comment, except ld_ Influence)
------------ | ------------- | ------------
Issue|ID|identifier
|NumPosts|the total number of posts under the same ID before closed
|StartTime|Issue created time
|EndTime|Issue closed time
|Duration|the days between endTime and startTime
|NumCommenters|the total number of people commented on the issue before closed
|NumLdPractices|the total number of leadership practices on the issue before closed
    NumNonLd    the number of comments are not leadership
|SetLdPractices|the set of leadership practices on the issue
||
Comment|IssueID|the issue ID which the comment is associated with
|Commenter|the author of the comment
|TimeStamp|the date/time the comment was made
|LdLabel|the label of the leadership practice
|WordCount|the number of word counts within the comment text
|HasLink|whether the comment provides a link to addtional information
|SentimentScore|the average sentiment score of the comment text
||
Developer|DevID|the developer identifier
|DaysOnProject|the number of days between the first and last comment
|NumberFollowers(all)|the number of followers from the community
|NumberFollowing((all))|the number of developers followed by the developer
|NumIssueComments|the total number of issues discussion participated
|NumCommits|the total number of commits
|NumPR|the total number of pull request initiated
|NumMerge|the total number of initiated pull request merged by project member
|AvgPostLength|the average word counts of his/her issue posts
|SetLdPractices|the set of leadership skills practiced by him/her
ld_influence||
|other_commenter|The number of commenter who is not the issue reporter or the author of this comment
|comment_num|The number of comments
|reporter_response|The number of comments posted by the issue reporter
|self_response|The number of comments posted by the author of this comment
|other_response|The number of comments posted by other commenters
|ld_num|The number of leadership comments
|ld_types|The number of leadership types
|word_divergence|set(words) / len(words)
|LD*|The number of leadership practices
=======
Granularity	Feature	Definition (The comment used does not contain the issue reporter's comment, except ld_ Influence)

Issue	ID	identifier

	NumPosts	the total number of posts under the same ID before closed
	
	StartTime	Issue created time
	EndTime	Issue closed time
	
	Duration	the days between endTime and startTime
	
	NumCommenters	the total number of people commented on the issue before closed
	
	NumLdPractices	the total number of leadership practices on the issue before closed
	
    NumNonLd    the number of comments are not leadership
    
	SetLdPractices	the set of leadership practices on the issue
	
		
Comment	IssueID	the issue ID which the comment is associated with
	Commenter	the author of the comment
	TimeStamp	the date/time the comment was made
	LdLabel	the label of the leadership practice
	WordCount	the number of word counts within the comment text
	HasLink	whether the comment provides a link to addtional information
	SentimentScore	the average sentiment score of the comment text
		
Developer	DevID	the developer identifier
	DaysOnProject	the number of days between the first and last comment
	NumberFollowers(all)	the number of followers from the community
	NumberFollowing((all))	the number of developers followed by the developer
	NumIssueComments	the total number of issues discussion participated
	NumCommits	the total number of commits
	NumPR	the total number of pull request initiated
	NumMerge	the total number of initiated pull request merged by project member
	AvgPostLength	the average word counts of his/her issue posts
	SetLdPractices	the set of leadership skills practiced by him/her
ld_influence		
	other_commenter	The number of commenter who is not the issue reporter or the author of this comment
	comment_num	The number of comments
	reporter_response	The number of comments posted by the issue reporter
	self_response	The number of comments posted by the author of this comment
	other_response	The number of comments posted by other commenters
	ld_num	The number of leadership comments
	ld_types	The number of leadership types
	word_divergence	set(words) / len(words)
	LD*	The number of leadership practices
>>>>>>> 1c2fed857f23d275399a6bafa492cb32a44b9ff9
