# Xiaohongshu AIGC Comments and Posts Dataset

This dataset is collected from the Xiaohongshu (Little Red Book) platform, focusing on user-generated content about Artificial Intelligence-Generated Content (AIGC). It covers various categories, including advertisement, automotive, fashion, food, literature, printing, sports, and technology. The dataset contains user comments and posts, with information such as user IDs, content, timestamps, likes, and sentiment analysis, which can be used to analyze public perceptions and attitudes toward AIGC.

## Dataset Overview

The dataset is organized as follows:

- **Data Directory**: The dataset is divided into several thematic folders (e.g., `ai-Advertisement`, `ai-technology`), with each folder containing data on comments and posts related to that theme.
- **File Structure**:
  - `Comments-<Theme>.csv`: Contains user comments for a specific theme.
  - `Post-<Theme>.csv`: Contains post data for a specific theme.

### Sample Data Structure

For example, in the `ai-technology` folder, the file `Comments-technological development.csv` includes the following fields:

| Field Name         | Description                             |
|--------------------|-----------------------------------------|
| comment_id         | Unique identifier for the comment       |
| create_time        | Creation timestamp                      |
| ip_location        | IP location of the user                 |
| note_id            | ID of the post the comment is linked to |
| content            | Content of the comment                  |
| user_id            | Unique identifier of the user           |
| nickname           | User’s nickname                         |
| avatar             | Link to the user's avatar               |
| sub_comment_count  | Number of sub-comments                  |
| parent_comment_id  | ID of the parent comment                |
| last_modify_ts     | Last modification timestamp             |
| like_count         | Number of likes                         |
| sentiment          | Sentiment of the comment (e.g., positive, negative) |

### Sample Data

```csv
comment_id,create_time,ip_location,note_id,content,user_id,nickname,avatar,sub_comment_count,parent_comment_id,last_modify_ts,like_count,sentiment
658e7ddd000000001a00e241,1703837149000,,658e7d1d0000000012004a26,"Six fingers aren’t obvious enough?",608af36300000000010063ee,momo,"https://sns-avatar-qc.xhscdn.com/avatar/1040g2...",303,0,1728458720283,28k,positive
658ef186000000001702da48,1703866758000,,658e7d1d0000000012004a26,"With this body type, there would be no collarbones sitting like that",58de279582ec3932ec4c73b5,"Momo in Renovation","https://sns-avatar-qc.xhscdn.com/avatar/58de27...",1059,0,1728458720285,15k,positive
```
