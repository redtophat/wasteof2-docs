# explore

### Get the top followed users on the explore page.

```http
GET /explore/users/top
```

### Gets trending posts.
(Adding `?timeframe` to the end of the URL fetches a set of trending posts from that time frame. The supported values for this parameter are: `week`, `month`, and `all`)

```http
GET /explore/posts/trending
```
