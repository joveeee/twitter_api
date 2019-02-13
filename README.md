# twitter_api
Mesg service for Twitter API

# Discord invitation


```bash
mesg-core service deploy https://github.com/joveeee/twitter_api
```

## Tasks

### getTweets

Task key: **getTweets**



#### Inputs

| **key** | **type** | **description** |
| --- | --- | --- |
| **screen_name** | `String` | Twitter account name ( https://twitter.com/mesgfoundation -> screen name will be just mesgfoundation ) 
| **count** | `Number` | Number of tweets to retrieve |
| **tweet_mode** | `String` | extended or none (if you need full tweet text - use extended  |


#### Outputs

##### error

Output key: **error**

Return a `messageError` with the error

| **key** | **type** | **description** |
| --- | --- | --- |
| **messageError** | `String` |  |

##### success

Output key: **success**

Return the array of tweet object ( tweet object inluce a lot of data, see Twitter API)

| **key** | **type** | **description** |
| --- | --- | --- |
| **transactionMessages** | `Array of objects` |  | |




