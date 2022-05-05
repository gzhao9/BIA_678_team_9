Granularity|Feature|Definition (The comment used does not contain the issue reporter's comment, except ld_ Influence)
------------ | ------------- | ------------
Issue||
1|ID|identifier
2|NumPosts|the total number of posts under the same ID before closed
3|StartTime|Issue created time
4|EndTime|Issue closed time
5|Duration|the days between endTime and startTime
6|NumCommenters|the total number of people commented on the issue before closed
7|NumLdPractices|the total number of leadership practices on the issue before closed
8|SetLdPractices|the set of leadership practices on the issue
||
Comment||
1|IssueID|the issue ID which the comment is associated with
2|Commenter|the author of the comment
3|TimeStamp|the date/time the comment was made
4|LdLabel|the label of the leadership practice
5|WordCount|the number of word counts within the comment text
6|HasLink|whether the comment provides a link to addtional information
7|SentimentScore|the average sentiment score of the comment text
||
Developer||
1|DevID|the developer identifier
2|DaysOnProject|the number of days between the first and last comment
3|NumberFollowers(all)|the number of followers from the community
4|NumberFollowing((all))|the number of developers followed by the developer
5|NumIssueComments|the total number of issues discussion participated
6|NumCommits|the total number of commits
7|NumPR|the total number of pull request initiated
8|NumMerge|the total number of initiated pull request merged by project member
9|AvgPostLength|the average word counts of his/her issue posts
10|SetLdPractices|the set of leadership skills practiced by him/her
||
ld_influence||
1|other_commenter|The number of commenter who is not the issue reporter or the author of this comment
2|comment_num|The number of comments
3|reporter_response|The number of comments posted by the issue reporter
4|self_response|The number of comments posted by the author of this comment
5|other_response|The number of comments posted by other commenters
6|ld_num|The number of leadership comments
7|ld_types|The number of leadership types
8|word_divergence|set(words) / len(words)
9|LD*|The number of leadership practices
