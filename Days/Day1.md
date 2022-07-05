# Day 1

Write Up: <br /><br />
<a href="https://infosecwriteups.com/story-of-a-really-cool-ssrf-bug-cf88a3800efc">1. Story of a really cool bug</a><br/>
<a href="https://medium.com/@shahjerry33/blind-ssrf-the-hide-seek-game-da9d0ecef2fb">2. Blind SSRF: The Hide and Seek game</a><br/><br/>
SSRF Tip by Shrey Shah:<br/>
When Testing for Blind SSRF  it is common that you’ll find a DNS lookup for the given Burp Collaborator domain, but no HTTP request. This happens because the application attempted to make HTTP request to domain, which caused initial DNS lookup but the actual HTTP request was blocked by the network-level filtering.If you find only the DNS lookup or DNS query then it is not a vulnerability, it is mandatory to have the HTTP response which will make it a valid vulnerability.

# Training
Red Tean Training: 
<a href="https://www.youtube.com/watch?v=EIHLXWnK1Dw">Red Team Adversary Emulation With Caldera</a>
by<a href="https://www.youtube.com/c/HackerSploit"> @HackerSploit</a>
