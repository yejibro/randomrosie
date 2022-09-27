# randomrosie
A set of scripts that carefully pick a perfect pic for your next post
(VERY true)

## Usage
First you need to generate a list of pics. Edit bin/rosielistgen with your
paths and run it
```
bin/rosielistgen
```
and then you can run `randomrosie` to get 2 random pics. You can put the script in your cronlist to get new pics regularly. To exec the script
every minute put
```
* * * * *	~/.yeji/randomrosie
```
in your `crontab -e`
