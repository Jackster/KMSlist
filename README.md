# KMS list
KMS List is a website that lists known KMS hosts that are active. 
It has a built-in KMS activation checker that tries to activate using the KMS server being tested. 
It also periodically checks the KMS hosts to see if they are alive. Hosts are sorted by most recently online. 
The table also lets you know what country the host is located in.

You can visit the site here, [kmslist.ddns.net](https://kmslist.ddns.net/).

![Screenshot of the website.](https://i.postimg.cc/RVbZZKYV/Screenshot-2023-12-24-021600.png)



## Please note. 
- This website is hosted as is. I do not provide support or SLAs.
- This website is for educational use only.
- I do not host KMS services myself.
- The website is basic, and I fully expect it to crash at random.
- The host location is based on MaxMind tables. Of which may be wrong or out of date.
- The source code for this project is not open to the public. Anyone who can program well would be able to make a better site than this in less time than I did. 

## ToDo List
- Add uptime monitoring so we can monitor hosts over time and provide a better ranking of KMS hosts.
- Use full country names instead of 2-character ISO codes.
- Add a ping feature so users can sort hosts based on the network latency between them and the KMS host.
- Check which KMS versions the server responds to.
- Add some debug info to the server checker and host list.
- Remove dead hosts after X days, or at least delist them from the website and check once a day to see if they are alive again.

## How to contact me
If you have anything to ask or suggest, please [raise an issue on this Git.](https://github.com/Jackster/KMSlist/issues/new)
