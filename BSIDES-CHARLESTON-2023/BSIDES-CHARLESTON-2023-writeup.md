# BSIDES-CHARLESTON-2023-writeup

This is my writeup for the BSides Charleston CTF that took place on 11-4-2023. We were tasked to obtain 3 flags from a target machine which we had to SSH into. There was no initial foothold required as they supplied us with the SSH credentials.

## Enumeration

After logging into the machine via SSH, I transferred over linpeas.sh via scp to check how I could privesc as soon as I got in.

```
scp linpeas.sh kingpwn@10.10.10.204:/tmp/linpeas.sh 
```

After running linpeas, I noticed that it picks up docker as a possible privesc point. I decide to focus on that later.

![1-linpeas-output.png](1-linpeas-output.png)

## Flag 1


## Flag 3

## Flag 2
