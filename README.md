# Soal Latihan Linux

1. `mkdir artists_who_can_sing; cd artists_who_can_sing`
2. `wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut' -O files.zip`
3. `unzip files.zip -d singing_tutorials/`
4. `cd singing_tutorials/; ls; ls -a`
5. `grep -r "FLAG{" . | grep "opera" | grep "NBAYoungboy" | cut -d'{' -f2 | cut -d '}' -f1 > flag.txt`
6. `cd .. ; wget https://files.catbox.moe/9l4qu8 -O plsrunmeiamnotamalwarefr`
7. `chmod +x plsrunmeiamnotamalwarefr && ./plsrunmeiamnotamalwarefr`
8. `ps aux`
9. `touch ransom.moolah ; ps aux`
10. `kill PID`
11. `sudo adduser yabadobadoo && sudo usermod -aG sudo yabadabadoo && id yabadabadoo && su - yabadabadoo`
12. `mkdir fufufafa/ && chmod 700 fufufafa/ && ls -ld fufufafa/ && cd fufufafa/`
13. `cd /var/tmp/pls_solve_this_puzzle && find . -name "*.html" -exec sh -c 'xxd -r -p "{}" | grep -a "FLAG"' \; > ~/fufufafa/flag2.txt`
14. `cp flag.txt ~/fufufafa/`
15. `sudo chown -R yabadabadoo:yabadabadoo pls_solve_this_puzzle/ && rm -r pls_solve_this_puzzle/`
