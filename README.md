# Utilizing Github API to assess repository populatrity
By default this script uess Github API to retireve the top 20 repositories with more than 1,000 followers.
The top X repositories can be adjusted using yaml file (see below)

- input:
by default the code prints the top 20 repositories with results more than 1000 followers
*optional* config.yml file can be provided with key:value pair top_n: interger

- example config.yml:
```
top_n: 15
```

- output:
bar plot of top x repositories