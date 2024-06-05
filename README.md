# LostWallets - BrutePool.com 
![wallet.dat](https://user-images.githubusercontent.com/82582647/172037651-a03c947c-e51e-4259-80c1-42588bf6d9b7.png)</br>
**Find password get 50% balance**</br>

Telegram group:
**https://t.me/found_wallets**

## How to find the password yourself
Download the latest version of hashcat [**here**](https://github.com/hashcat/hashcat/releases)</br>
An example of using masks in hashcat is [**here**](https://cheatsheet.haax.fr/passcracking-hashfiles/hashcat_cheatsheet/)</br>
The hashes of the passwords from all wallets is in the file [**hashes.txt**](https://github.com/phrutis/LostWallets/blob/main/hashes.txt) Update 05.06.2024</br>

## Example of starting a search
TEST: ```hashcat.exe -m 11300 -a 3 test.txt foot?l?l?l?l -D 2 -w 3 -o FOUND.txt```</br>
Examples:</br>
Run: ```hashcat.exe -m 11300 -a 3 hashes.txt ?a?a?a?a?a?a?a?a -D 2 -w 3 -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 7 --increment hashes.txt -1 ?l?d ?l?l?l?l?1?1?1?1 prefix.txt -D 2 -w 3 -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 1 hashes.txt WORDLIST.txt WORDLIST2.txt -D 2 -w 3 -S -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 3 --increment --increment-min=4 --increment-max=8 hashes.txt ?a?a?a?a?a?a?a?a -D 2 -w 3 -o FOUND.txt```</br>
Use your password search prefixes by mask or [dictionaries](https://www.weakpass.com/wordlist)</br>

If you manage to find the password, write to me in telegram ```phrutis```<hr>

## Search in the pool
### Windows

Download http://www.brutepool.com/agents.php?download=1<br>
Create Folder POOL on Desktop<br>
Drag zip downloaded above into it<br>
Do not unzip<br>
Open CMD prompt in Folder<br>
```py hashtopolis.zip --url http://www.brutepool.com/api/server.php --voucher brutepool```<hr>

### Vast.ai

nvidia/cuda:12.0.0-devel-ubuntu20.04 with Jupyter<br>
Run a jupyter-python notebook<br>
Use Jupyter Lab interface<br>
After Startup, Click on OPEN<br>
Click on terminal<br>
``mkdir POOL``<br><br>
```cd POOL```<br><br>
```wget http://www.brutepool.com/agents.php?download=1 -O hashtopolis.zip```<br><br>
```pip install psutil```<br><br>
```pip install requests```<br><br>
```python3 hashtopolis.zip --url http://www.brutepool.com/api/server.php --voucher brutepool```<hr>

### Ubuntu (Linux)

Desktop Version<br>
```mkdir POOL```<br><br>
```cd POOL```<br><br>
```wget http://www.brutepool.com/agents.php?download=1 -O hashtopolis.zip```<br><br>
```pip install psutil```<br><br>
```pip install requests```<br><br>
```python3 hashtopolis.zip --url http://www.brutepool.com/api/server.php --voucher brutepool```<hr>

### Hiveos
```sudo apt update && sudo apt-get update && sudo apt install git && sudo apt-get install python3-pip -y && sudo -H python3 -m pip install psutil && sudo -H pip3 install requests && sudo mkdir CAT && cd CAT && wget http://www.brutepool.com/agents.php?download=1 && python3 agents.php?download=1 && http://www.brutepool.com/api/server.php && brutepool```<hr>

After Connecting to Server using one of the below steps<br>
SERVER: http://brutepool.com<br>
Login: hunter<br>
Password: hunter<br>
Find your Agent ID and Post in [**Telegram Group**](https://t.me/found_wallets) so it can be assigned to you.<hr>

- [**FAQ**](https://github.com/phrutis/LostWallets/edit/main/README.md#frequently-asked-questions)
- [**Fake wallets**](https://github.com/phrutis/LostWallets/tree/main/fake-wallets)</br>
- [**Founds wallets**](https://github.com/phrutis/LostWallets/tree/main/Found_wallets)

### Partner addresses 25%
1️⃣ - 1NEFQpE4qETrAtzzRD8vLGs8FRZmUsV6FF (02.03.2022)</br>
2️⃣ - bc1qphhedzu5jg7emtw09akwzzdh03mqaytett9zlz (26.03.2022)</br>
3️⃣ - 1NoName1LLKRfLmoh9jawLWrf6t185bC7v (31.03.2022)</br>
4️⃣ - bc1q5k000jhfklq8k82lpf8fz9cwffj4murvt7kxpm (11.04.2022)</br>
5️⃣ - bc1qgdgr02whvzkzqcqhpstqepq8sjcc4ljgyfnka9 (20.04.2022)</br>
6️⃣ - bc1q7rkc2ul0p033rlp32jauvuq74kmvxvlnjdegxe (29.05.2024)</br>
7️⃣ - bc1qvpmhsrr4m8k2tu35am9lj3u5hvq7penp6un52p (04.06.2024)</br>
8️⃣ -

|   |  Wallet name    | Address   | Your reward  |  | Partner | Update |
|:--|:----------------|:----------|:-------------|:-|:--------|:-------|
| 1 | 10000.00417651.dat | [1LfV1tSt3KNyHpFJnAzrqsLFdeD2EvU1MK](https://www.blockchain.com/btc/address/1LfV1tSt3KNyHpFJnAzrqsLFdeD2EvU1MK) | 50% | 🔓 | 3 | 05.06.2024 |
| 2 | 5000.01168565.dat | [18xGHNrU26w6HSCEL8DD5o1whfiDaYgp6i](https://www.blockchain.com/btc/address/18xGHNrU26w6HSCEL8DD5o1whfiDaYgp6i) | 50% | 🔓 | 1 | 05.06.2024 |
| 3 | 4000.dat | [18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM](https://www.blockchain.com/btc/address/18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM) | 50% | :lock: | 2 | 05.06.2024 |
| 4 | 4000.00222015.dat | [18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM](https://www.blockchain.com/btc/address/18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM) | 50% | :lock: | 2 | 05.06.2024 |
| 5 | 478.33.dat | [11.10](https://www.blockchain.com/btc/address/1QBMmD24baHgusrqUSXc9s1uALtHeuJsjK) + [203.50](https://www.blockchain.com/btc/address/1NUnbngzRB2SeMqZLrLrypoYW5FrusVU3X) + [76.70](https://www.blockchain.com/btc/address/1JXvzLcpxh3LBvEi1NKE6qAVpft6khkpWN) + [103.78](https://www.blockchain.com/btc/address/1A6R1sEkzpkNPx5hdJHjmN3947qYXFxuHz) + [83.25](https://www.blockchain.com/btc/address/187oyQbBSRx8azGY8EC3V9oTsm6bTD45Zb) | 50% | :lock: | 1 | 05.06.2024 |
| 6 | 405.00120319.dat | [1An4jHFsSz31TjW49vsZtCt2SXKV7oHRWb](https://www.blockchain.com/btc/address/1An4jHFsSz31TjW49vsZtCt2SXKV7oHRWb) | 50% | :lock: | 1 | 05.06.2024 |
| 7 | 340.00283740.dat | [1JqPFnGPhHhy54zJKmC1MPiczzgFjCmzE9](https://www.blockchain.com/btc/address/1JqPFnGPhHhy54zJKmC1MPiczzgFjCmzE9) | 50% | :lock: | 1 | 05.06.2024 |
| 8 | 319.00053581.dat | [1FJBeYLRArReqVTiqwYTEc9hAfypGx8MyN](https://www.blockchain.com/btc/address/1FJBeYLRArReqVTiqwYTEc9hAfypGx8MyN) | 50% | :lock: | 1 | 05.06.2024 |
| 9 | 300.00055278.dat | [1LbvdyYr5KH8fZhXJ7txBr1RjoDnzhQEqY](https://www.blockchain.com/btc/address/1LbvdyYr5KH8fZhXJ7txBr1RjoDnzhQEqY) | 50% | :lock: | 1 | 05.06.2024 |
| 10 | 252.20004225.dat | [1GYLfNfMesF3YrwVU94P5wtcJjhAx9DLYy](https://www.blockchain.com/btc/address/1GYLfNfMesF3YrwVU94P5wtcJjhAx9DLYy) | 50% | :lock: | 1 | 05.06.2024 |
| 11 | 200.00224825.dat | [1DDYt8kJE1JBa2kQN1R921weJGbCnWcgG4](https://www.blockchain.com/btc/address/1DDYt8kJE1JBa2kQN1R921weJGbCnWcgG4) | 50% | 🔓 | 1 | 05.06.2024 |
| 12 | 198.00412439.dat | [1E87cVPLZ938w7vYEA1e9RWSc8mESPA3J5](https://www.blockchain.com/btc/address/1E87cVPLZ938w7vYEA1e9RWSc8mESPA3J5) | 50% | :lock: | 1 | 05.06.2024 |
| 13 | 186.29379209.dat | [16vMxeMHJDbMoDu2s1ozDQAmzY3bPmdLLi](https://www.blockchain.com/btc/address/16vMxeMHJDbMoDu2s1ozDQAmzY3bPmdLLi) | 50% | 🔓 | 3 | 05.06.2024 |
| 14 | 180.77714198.dat | [1DCqdVEh91bVzEShe6iU5iuNrd1LbsWvgf](https://www.blockchain.com/btc/address/1DCqdVEh91bVzEShe6iU5iuNrd1LbsWvgf) | 50% | :lock: | 1 | 05.06.2024 |
| 15 | 177.74326390.dat | [1BiA2yvL3GWuGGVr7v1cGCbH6WPYvoG4tL](https://www.blockchain.com/btc/address/1BiA2yvL3GWuGGVr7v1cGCbH6WPYvoG4tL) | 50% | :lock: | 3 | 05.06.2024 |
| 16 | 159.89913129.dat | [12PpzLTHNWCLsHPgHMNd9ebj7bwbTxs33u](https://www.blockchain.com/btc/address/12PpzLTHNWCLsHPgHMNd9ebj7bwbTxs33u) | 50% | :lock: | 1 | 05.06.2024 |
| 17 | 131.63.dat | [31.63](https://www.blockchain.com/btc/address/1EZeYuLR2ugK8sk4XeDVcyNGBT7sGPDrNb) + [50.00](https://www.blockchain.com/btc/address/1DFo9TYjyKT7Rwa1Nx7G3STMRHBFUC2hUB) + [50.00](https://www.blockchain.com/btc/address/1EdrQwSXQYFKZKim3fX7jKTiR5gmjsjT64) | 50% | :lock: | 4 | 05.06.2024 |
| 18 | 130.00000547.dat | [1P2kKdepEAJQwVHoaodfQKD6jSJC86z1Yw](https://www.blockchain.com/btc/address/1P2kKdepEAJQwVHoaodfQKD6jSJC86z1Yw) | 50% | :lock: | 1 | 05.06.2024 |
| 19 | 129.66226125.dat | [1AamCcS7oXPZYvYw7dwcZxjxJkPSxZ94vm](https://www.blockchain.com/btc/address/1AamCcS7oXPZYvYw7dwcZxjxJkPSxZ94vm) | 50% | :lock: | 1 | 05.06.2024 |
| 20 | 108.06001094.dat | [1G3hJ3CJdovXiTyK1AWQpTevW1hHCQ7jsM](https://www.blockchain.com/btc/address/1G3hJ3CJdovXiTyK1AWQpTevW1hHCQ7jsM) | 50% | :lock: | 1 | 05.06.2024 |
| 21 | 108.06001094-2.dat | [1G3hJ3CJdovXiTyK1AWQpTevW1hHCQ7jsM](https://www.blockchain.com/btc/address/1G3hJ3CJdovXiTyK1AWQpTevW1hHCQ7jsM) | 50% | :lock: | 1 | 05.06.2024 |
| 22 | 105.11031599.dat | [52.97191089](https://www.blockchain.com/btc/address/15wx2WPf67P9AqrMUPzcePzzDFa7pJmhud) + [52.13840510](https://www.blockchain.com/btc/address/1GtR4VXdRNMqnABAiAgGYnB4yQyWZ2ZTWk) | 50% | :lock: | 1 | 05.06.2024 |
| 23 | 99.99901094.dat | [1Gj2KiTy9SFtuFSJECmpePseYchhkU3gXQ](https://www.blockchain.com/btc/address/1Gj2KiTy9SFtuFSJECmpePseYchhkU3gXQ) | 50% | :lock: | 4 | 05.06.2024 |
| 24 | 91.00501641.dat | [1BvNsod2wBpjoJmYmbnhk1j9FLLWz7HzZE](https://www.blockchain.com/btc/address/1BvNsod2wBpjoJmYmbnhk1j9FLLWz7HzZE) | 50% | :lock: | 1 | 05.06.2024 |
| 25 | 90.59781094.dat | [73.50781094](https://www.blockchain.com/btc/address/18EGA8nGHjA998Qc17je6K8T6UUDHxeoCH) + [17.09000000](https://www.blockchain.com/btc/address/182RVphMRdEe9i5A4EikLx8RH1EenFBeCG) | 50% | :lock: | 5 | 05.06.2024 |
| 26 | 87.86507229.dat | [1PYeoCUYbq6zsh7BcyRgeAQdkFGnhCY95T](https://www.blockchain.com/btc/address/1PYeoCUYbq6zsh7BcyRgeAQdkFGnhCY95T) | 50% | :lock: | 1 | 05.06.2024 |
| 27 | 78.65929782.dat | [1Pq2Y45aDfwGn6pKFGv8enKgNR2efw4jFW](https://www.blockchain.com/btc/address/1Pq2Y45aDfwGn6pKFGv8enKgNR2efw4jFW) | 50% | :lock: | 3 | 05.06.2024 |
| 28 | 78.60361094.dat | [1BSmyTdYpsHA5JhLS9azGmVADuJRiLWE5Z](https://www.blockchain.com/btc/address/1BSmyTdYpsHA5JhLS9azGmVADuJRiLWE5Z) | 50% | :lock: | 1 | 05.06.2024 |
| 29 | 77.98600547.dat | [14tZU9KyHXwkGXkVUKehkMfaEZ8ad7jwNc](https://www.blockchain.com/btc/address/14tZU9KyHXwkGXkVUKehkMfaEZ8ad7jwNc) | 50% | :lock: | 1 | 05.06.2024 |
| 30 | 74.16883731.dat | [1F11GQNQKTEme6L74c5dVTTMkD7ME2jiqP](https://www.blockchain.com/btc/address/1F11GQNQKTEme6L74c5dVTTMkD7ME2jiqP) | 50% | :lock: | 1 | 05.06.2024 |
| 31 | 73.50781094.dat | [18EGA8nGHjA998Qc17je6K8T6UUDHxeoCH](https://www.blockchain.com/btc/address/18EGA8nGHjA998Qc17je6K8T6UUDHxeoCH) | 50% | :lock: | 1 | 05.06.2024 |
| 32 | 70.01000000.dat | [17w8w8ZHdqkSYFkhAMfHJaEqCHgHm9egKv](https://www.blockchain.com/btc/address/17w8w8ZHdqkSYFkhAMfHJaEqCHgHm9egKv) | 50% | :lock: | 1 | 05.06.2024 |
| 33 | 52.55001760.dat | [13KKv3ywwJ5WYovLgiCAaqpCVuMDEF6oxo](https://www.blockchain.com/btc/address/13KKv3ywwJ5WYovLgiCAaqpCVuMDEF6oxo) | 50% | :lock: | 1 | 05.06.2024 |
| 34 | 52.08001094.dat | [15Ybt9WjCF5ABAZ1GjFVTjzV3dJH5f9USh](https://www.blockchain.com/btc/address/15Ybt9WjCF5ABAZ1GjFVTjzV3dJH5f9USh) | 50% | :lock: | 1 | 05.06.2024 |
| 35 | 50.43201094.dat | [1QFDAGXRkhNYfx2mHEu81QH8dAj4go4A8d](https://www.blockchain.com/btc/address/1QFDAGXRkhNYfx2mHEu81QH8dAj4go4A8d) | 50% | :lock: | 1 | 05.06.2024 |
| 36 | 50.18338758.dat | [1NyEeyXu8ydNw67e3ZTUmkwQJ8QNd1o3cF](https://www.blockchain.com/btc/address/1NyEeyXu8ydNw67e3ZTUmkwQJ8QNd1o3cF) | 50% | 🔓 | 3 | 05.06.2024 |
| 37 | 50.00011641.dat | [1MtXD6gGHZB1cAcP1Du29Ho9KobMCYD7ZC](https://www.blockchain.com/btc/address/1MtXD6gGHZB1cAcP1Du29Ho9KobMCYD7ZC) | 50% | :lock: | 3 | 05.06.2024 |
| 38 | 50.00004046.dat | [13vq3LDCBpwbyxSenJDpHWt3xCXgbtzp9V](https://www.blockchain.com/btc/address/13vq3LDCBpwbyxSenJDpHWt3xCXgbtzp9V) | 50% | :lock: | 4 | 05.06.2024 |
| 39 | 50.00003282.dat | [1E4ad5bA8HgbqxsPYpmDtVRNBRF2XfqTns](https://www.blockchain.com/btc/address/1E4ad5bA8HgbqxsPYpmDtVRNBRF2XfqTns) | 50% | :lock: | 1 | 05.06.2024 |
| 40 | 50.00002188.dat | [1KTvsW5tg5gkJf9fyT2xsvjkv7dzuZNTpW](https://www.blockchain.com/btc/address/1KTvsW5tg5gkJf9fyT2xsvjkv7dzuZNTpW) | 50% | :lock: | 1 | 05.06.2024 |
| 41 | 50.00001641.dat | [1JHqAnwohyhXgvwNnzEMeMwejsf6vHZhgp](https://www.blockchain.com/btc/address/1JHqAnwohyhXgvwNnzEMeMwejsf6vHZhgp) | 50% | :lock: | 4 | 05.06.2024 |
| 42 | 50.00001641-2.dat | [18h7ETAzcqRCGNXTstWSavrvhy5S5YKsQF](https://www.blockchain.com/btc/address/18h7ETAzcqRCGNXTstWSavrvhy5S5YKsQF) | 50% | :lock: | 4 | 05.06.2024 |
| 43 | 50.00000547.dat | [1Aw6miK9me2AijQ76Q32NkPa1B7buWqWPg](https://www.blockchain.com/btc/address/1Aw6miK9me2AijQ76Q32NkPa1B7buWqWPg) | 50% | :lock: | 1 | 05.06.2024 |
| 44 | 48.92440002.dat | [18rB6Uh5tGTu1TftZ8swNgzp9DtieJaWhz](https://www.blockchain.com/btc/address/18rB6Uh5tGTu1TftZ8swNgzp9DtieJaWhz) | 50% | :lock: | 1 | 05.06.2024 |
| 45 | 42.53718329.dat | [1NKmf6GszBQ6wo349LUT4Je1csNyDDpb5Y](https://www.blockchain.com/btc/address/1NKmf6GszBQ6wo349LUT4Je1csNyDDpb5Y) | 50% | :lock: | 3 | 05.06.2024 |
| 46 | 32.85679433.dat | [15r2tRv6B47zGFrCFsUSxtGtxxKVN6KAUc](https://www.blockchain.com/btc/address/15r2tRv6B47zGFrCFsUSxtGtxxKVN6KAUc) | 50% | :lock: | 1 | 05.06.2024 |
| 47 | 31.63000580.dat | [1EZeYuLR2ugK8sk4XeDVcyNGBT7sGPDrNb](https://www.blockchain.com/btc/address/1EZeYuLR2ugK8sk4XeDVcyNGBT7sGPDrNb) | 50% | :lock: | 4 | 05.06.2024 |
| 48 | 31.01002188.dat | [14J2wsejqNKtrEpAe1ziQVHQHFE3yX6bKB](https://www.blockchain.com/btc/address/14J2wsejqNKtrEpAe1ziQVHQHFE3yX6bKB) | 50% | :lock: | 3 | 05.06.2024 |
| 49 | 30.99098222.dat | [18jANvQ6AuVGJnea4EhmXiAf6bHR5qKjPB](https://www.blockchain.com/btc/address/18jANvQ6AuVGJnea4EhmXiAf6bHR5qKjPB) | 50% | :lock: | 3 | 05.06.2024 |
| 50 | 28.00001000.dat | [1PbHeg1WDosvuhApxbfQg3iFDQ2WW7Mttf](https://www.blockchain.com/btc/address/1PbHeg1WDosvuhApxbfQg3iFDQ2WW7Mttf) | 50% | :lock: | 4 | 05.06.2024 |
| 51 | 27.03768216.dat | [1rhYqDz3WEbCSQM54bGguTnJkmLQwV3d5](https://www.blockchain.com/btc/address/1rhYqDz3WEbCSQM54bGguTnJkmLQwV3d5) | 50% | :lock: | 3 | 05.06.2024 |
| 52 | 25.99960547.dat | [1JSTCtS21CFqBz2ZQT4X9sTeCoy58FwtDj](https://www.blockchain.com/btc/address/1JSTCtS21CFqBz2ZQT4X9sTeCoy58FwtDj) | 50% | :lock: | 3 | 05.06.2024 |
| 53 | 25.00101641.dat | [14PcoSTA1g2k1t2W5jg1S9zc5Si8ToQxke](https://www.blockchain.com/btc/address/14PcoSTA1g2k1t2W5jg1S9zc5Si8ToQxke) | 50% | :lock: | 1 | 05.06.2024 |
| 54 | 25.00011094.dat | [12BycRrxPivnhnwfD5qfKaE7ccAc1qhrCb](https://www.blockchain.com/btc/address/12BycRrxPivnhnwfD5qfKaE7ccAc1qhrCb) | 50% | :lock: | 1 | 05.06.2024 |
| 55 | 22.85001641.dat | [19Hj5Pzi4hCj12porw97i183XYTrScbtXS](https://www.blockchain.com/btc/address/19Hj5Pzi4hCj12porw97i183XYTrScbtXS) | 50% | :lock: | 3 | 05.06.2024 |
| 56 | 21.89679859.dat | [1HBXJBXWYM1jZd8p1ff2a4uhJxvtgoXiYU](https://www.blockchain.com/btc/address/1HBXJBXWYM1jZd8p1ff2a4uhJxvtgoXiYU) | 50% | :lock: | 1 | 05.06.2024 |
| 57 | 20.11001641.dat | [1NuPEefRU2AZ319x45fY5wBHBV2Z72PY98](https://www.blockchain.com/btc/address/1NuPEefRU2AZ319x45fY5wBHBV2Z72PY98) | 50% | :lock: | 1 | 05.06.2024 |
| 58 | 20.00241094.dat | [1F3yxoWp5TdpVzbziVJ2VnvhpaXJma3qnF](https://www.blockchain.com/btc/address/1F3yxoWp5TdpVzbziVJ2VnvhpaXJma3qnF) | 50% | :lock: | 1 | 05.06.2024 |
| 59 | 19.88790000.dat | [19hZHgZt94uXxSJhWDqxMpEZmN3ctvVFvH](https://www.blockchain.com/btc/address/19hZHgZt94uXxSJhWDqxMpEZmN3ctvVFvH) | 50% | :lock: | 1 | 05.06.2024 |
| 60 | 19.43300547.dat | [18H3tXBX9fC2AguKV2m34YKHYugN1Y4XkA](https://www.blockchain.com/btc/address/18H3tXBX9fC2AguKV2m34YKHYugN1Y4XkA) | 50% | :lock: | 1 | 05.06.2024 |
| 61 | 19.33608000.dat | [1HuTxwnZMyaNRTsHJ2Xg83Z7mt75dtdwC3](https://www.blockchain.com/btc/address/1HuTxwnZMyaNRTsHJ2Xg83Z7mt75dtdwC3) | 50% | :lock: | 1 | 05.06.2024 |
| 62 | 19.30000000.dat | [18HKjVPJwfDg7TDSpoVh2KBiTQny6hymMX](https://www.blockchain.com/btc/address/18HKjVPJwfDg7TDSpoVh2KBiTQny6hymMX) | 50% | :lock: | 1 | 05.06.2024 |
| 63 | 19.28011668.dat | [1EREjjsLgB5JJQhN89gQR9PvH89yWJ4kuV](https://www.blockchain.com/btc/address/1EREjjsLgB5JJQhN89gQR9PvH89yWJ4kuV) | 50% | :lock: | 1 | 05.06.2024 |
| 64 | 18.72704494.dat | [1LSmeqqYoyGAxUwLxmkvuDU6LGM2FGf6AS](https://www.blockchain.com/btc/address/1LSmeqqYoyGAxUwLxmkvuDU6LGM2FGf6AS) | 50% | :lock: | 1 | 05.06.2024 |
| 65 | 18.17000000.dat | [1EM7FJV7L3CJZuH6SFTpYnmbMi9RXKdwK6](https://www.blockchain.com/btc/address/1EM7FJV7L3CJZuH6SFTpYnmbMi9RXKdwK6) | 50% | :lock: | 3 | 05.06.2024 |
| 66 | 18.00000000.dat | [1B5FuKQgmPg4SJsCjFU3svrFPpZpQZMU1d](https://www.blockchain.com/btc/address/1B5FuKQgmPg4SJsCjFU3svrFPpZpQZMU1d) | 50% | :lock: | 1 | 05.06.2024 |
| 67 | 17.82900000.dat | [1LwQU2kqdH6dLSsizstNxrhqk7XhCMLMF3](https://www.blockchain.com/btc/address/1LwQU2kqdH6dLSsizstNxrhqk7XhCMLMF3) | 50% | :lock: | 4 | 05.06.2024 |
| 68 | 17.82021465.dat | [17ixLGdJQDdS76Un535rzbtxJNjmAJFqac](https://www.blockchain.com/btc/address/17ixLGdJQDdS76Un535rzbtxJNjmAJFqac) | 50% | :lock: | 1 | 05.06.2024 |
| 69 | 17.20100000.dat | [13q3UMbUdqak1xX385aZc3MmtdMtNfsnSU](https://www.blockchain.com/btc/address/13q3UMbUdqak1xX385aZc3MmtdMtNfsnSU) | 50% | :lock: | 1 | 05.06.2024 |
| 70 | 17.19060793.dat | [1LJxQSJ1uf2VHq4RDZgHQgEwn8JRAr6btq](https://www.blockchain.com/btc/address/1LJxQSJ1uf2VHq4RDZgHQgEwn8JRAr6btq) | 50% | :lock: | 1 | 05.06.2024 |
| 71 | 17.09000666.dat | [1NFp8YqgBjSRFdgWt7ynmojG8gpQDjVDpJ](https://www.blockchain.com/btc/address/1NFp8YqgBjSRFdgWt7ynmojG8gpQDjVDpJ) | 50% | :lock: | 1 | 05.06.2024 |
| 72 | 17.08998980.dat | [16Wi4S2Dn9sK2VVtP5EgA3UP1zEry6oY8X](https://www.blockchain.com/btc/address/16Wi4S2Dn9sK2VVtP5EgA3UP1zEry6oY8X) | 50% | 🔓 | 1 | 05.06.2024 |
| 73 | 16.23030002.dat | [15npoeYGso1qyFAo7Wzw35s4fXMDh5ryrj](https://www.blockchain.com/btc/address/15npoeYGso1qyFAo7Wzw35s4fXMDh5ryrj) | 50% | :lock: | 1 | 05.06.2024 |
| 74 | 16.13643422.dat | [14jt9AzqeM1TX3oQCGWkQbtfeUYih3o56W](https://www.blockchain.com/btc/address/14jt9AzqeM1TX3oQCGWkQbtfeUYih3o56W) | 50% | :lock: | 1 | 05.06.2024 |
| 75 | 15.99100158.dat | [12ie6iDXeyBcyjSgdrs8Jo5eUbHg4r2N7Q](https://www.blockchain.com/btc/address/12ie6iDXeyBcyjSgdrs8Jo5eUbHg4r2N7Q) | 50% | :lock: | 3 | 05.06.2024 |
| 76 | 15.75044635.dat | [1H9WV22GeCQuTGQbwTEQfGZhvTVhNsscNr](https://www.blockchain.com/btc/address/1H9WV22GeCQuTGQbwTEQfGZhvTVhNsscNr) | 50% | :lock: | 1 | 05.06.2024 |
| 77 | 15.71719998.dat | [1Lefr9kXBybeW4SG1KtpysnnKKftnDYTvP](https://www.blockchain.com/btc/address/1Lefr9kXBybeW4SG1KtpysnnKKftnDYTvP) | 50% | :lock: | 1 | 05.06.2024 |
| 78 | 15.01812238.dat | [18snvPxfy9SGZUNe9i7kUJced3PEdVWodm](https://www.blockchain.com/btc/address/18snvPxfy9SGZUNe9i7kUJced3PEdVWodm) | 50% | :lock: | 1 | 05.06.2024 |
| 79 | 14.77500000.dat | [1LhKQqkjzxxzve61HYytPYJ7oVMh88aV4T](https://www.blockchain.com/btc/address/1LhKQqkjzxxzve61HYytPYJ7oVMh88aV4T) | 50% | :lock: | 1 | 05.06.2024 |
| 80 | 14.70456309.dat | [1AHgGcw8LjzhsRKtKxjvyRSUSAnkcAEMjX](https://www.blockchain.com/btc/address/1AHgGcw8LjzhsRKtKxjvyRSUSAnkcAEMjX) | 50% | :lock: | 1 | 05.06.2024 |
| 81 | 14.60000000.dat | [15LhbzoCjr9icNTsabMVBKCgTZYqPHgcaf](https://www.blockchain.com/btc/address/15LhbzoCjr9icNTsabMVBKCgTZYqPHgcaf) | 50% | :lock: | 1 | 05.06.2024 |
| 82 | 14.35226342.dat | [1AYyMBbxXv9E29qJoTpbd6ocje81ZAJQsF](https://www.blockchain.com/btc/address/1AYyMBbxXv9E29qJoTpbd6ocje81ZAJQsF) | 50% | :lock: | 3 | 05.06.2024 |
| 83 | 14.09013974.dat | [1GDcVTrZNhVFt7pEnwvHfepoth6mqHVVvq](https://www.blockchain.com/btc/address/1GDcVTrZNhVFt7pEnwvHfepoth6mqHVVvq) | 50% | :lock: | 4 | 05.06.2024 |
| 84 | 14.00010000.dat | [177a2RmG1nn78BQpjAyuEztvv24dXdns7r](https://www.blockchain.com/btc/address/177a2RmG1nn78BQpjAyuEztvv24dXdns7r) | 50% | :lock: | 1 | 05.06.2024 |
| 85 | 13.76858117.dat | [1LmdsdywkMNqgXg7x7q88NT2WeXXf52co3](https://www.blockchain.com/btc/address/1LmdsdywkMNqgXg7x7q88NT2WeXXf52co3) | 50% | :lock: | 1 | 05.06.2024 |
| 86 | 13.47094589.dat | [1DphS33aWDZBWNEh3rPJFfD6GFP1mmgerU](https://www.blockchain.com/btc/address/1DphS33aWDZBWNEh3rPJFfD6GFP1mmgerU) | 50% | :lock: | 1 | 05.06.2024 |
| 87 | 12.82192064.dat | [19tLSCZWhX5YBVy6uX2kLheNjdUb9RBojS](https://www.blockchain.com/btc/address/19tLSCZWhX5YBVy6uX2kLheNjdUb9RBojS) | 50% | :lock: | 1 | 05.06.2024 |
| 88 | 11.26827053.dat | [1NibfhHfgA857dtG6pB25Y5hDcxpDo2J47](https://www.blockchain.com/btc/address/1NibfhHfgA857dtG6pB25Y5hDcxpDo2J47) | 50% | :lock: | 1 | 05.06.2024 |
| 89 | 10.83091000.dat | [1MB28otoAQFpP9ywiA8CbYVSKHpSTBH1z6](https://www.blockchain.com/btc/address/1MB28otoAQFpP9ywiA8CbYVSKHpSTBH1z6) | 50% | :lock: | 3 | 05.06.2024 |
| 90 | 10.50200000.dat | [14PEUoKuRB9Q7yfS94cRXh2XugsrBxbxAo](https://www.blockchain.com/btc/address/14PEUoKuRB9Q7yfS94cRXh2XugsrBxbxAo) | 50% | :lock: | 3 | 05.06.2024 |
| 91 | 10.21000001.dat | [1L3amZhWgU8vnGzeMKJc4QFqvQhpU53WsV](https://www.blockchain.com/btc/address/1L3amZhWgU8vnGzeMKJc4QFqvQhpU53WsV) | 50% | :lock: | 1 | 05.06.2024 |
| 92 | 8.90000000.dat | [1LHjrPBeEYQv1f219VQcQ71EBpwvp3hdD5](https://www.blockchain.com/btc/address/1LHjrPBeEYQv1f219VQcQ71EBpwvp3hdD5) | 50% | :lock: | 4 | 05.06.2024 |
| 93 | 8.77089137.dat | [16Na4QHvS2rEP23igjKYfgoPqUYtZvzB5d](https://www.blockchain.com/btc/address/16Na4QHvS2rEP23igjKYfgoPqUYtZvzB5d) | 50% | 🔓 | 1 | 05.06.2024 |
| 94 | 8.50023481.dat | [1KDUcZh5Z6H1of4Pwoy5ojJtkQxcQBHhnH](https://www.blockchain.com/btc/address/1KDUcZh5Z6H1of4Pwoy5ojJtkQxcQBHhnH) | 50% | :lock: | 3 | 05.06.2024 |
| 95 | 7.00000000.dat | [1MsbUGxbcW1zKvTbNq86rvteu6zm7h7Nfw](https://www.blockchain.com/btc/address/1MsbUGxbcW1zKvTbNq86rvteu6zm7h7Nfw) | 50% | :lock: | 1 | 05.06.2024 |
| 96 | 6.33718357.dat | [18fH6tk7KG998cSKXTg7v3wqLHuVu7es4i](https://www.blockchain.com/btc/address/18fH6tk7KG998cSKXTg7v3wqLHuVu7es4i) | 50% | :lock: | 1 | 05.06.2024 |
| 97 | 6.33560000.dat | [1LYdAMbjcbD8RsnThMz3HwhaGb1keyedjx](https://www.blockchain.com/btc/address/1LYdAMbjcbD8RsnThMz3HwhaGb1keyedjx) | 50% | :lock: | 1 | 05.06.2024 |
| 98 | 6.29000000.dat | [13LjzkgZQoHoUEo9CsbLJwGcc8zmnhQrRy](https://www.blockchain.com/btc/address/13LjzkgZQoHoUEo9CsbLJwGcc8zmnhQrRy) | 50% | :lock: | 1 | 05.06.2024 |
| 99 | 6.19445176.dat | [1NyECGXWqQdoNUCvNN94CoCC97AgBQcv2o](https://www.blockchain.com/btc/address/1NyECGXWqQdoNUCvNN94CoCC97AgBQcv2o) | 50% | :lock: | 1 | 05.06.2024 |
| 100 | 6.00000000.dat | [1L1iJNKBubV4KbScgKTYS85gjvBmoDpzST](https://www.blockchain.com/btc/address/1L1iJNKBubV4KbScgKTYS85gjvBmoDpzST) | 50% | :lock: | 1 | 05.06.2024 |
| 101 | 5.89290000.dat | [1MnMPxYFL6hfCRmQxm1HxyChP7CvaCDaja](https://www.blockchain.com/btc/address/1MnMPxYFL6hfCRmQxm1HxyChP7CvaCDaja) | 50% | :lock: | 1 | 05.06.2024 |
| 102 | 5.86332001.dat | [16M7J5ThnZ8TdoTzyS9nrY1c9V7gjjxmbt](https://www.blockchain.com/btc/address/16M7J5ThnZ8TdoTzyS9nrY1c9V7gjjxmbt) | 50% | :lock: | 4 | 05.06.2024 |
| 103 | 5.08877624.dat | [15zMovc6E134wsPKWXhF364DsQXkLV7wcX](https://www.blockchain.com/btc/address/15zMovc6E134wsPKWXhF364DsQXkLV7wcX) | 50% | :lock: | 1 | 05.06.2024 |
| 104 | 5.05538396.dat | [1JEsngBPtTs56qdx7UT3VzkusdmEBPAXCy](https://www.blockchain.com/btc/address/1JEsngBPtTs56qdx7UT3VzkusdmEBPAXCy) | 50% | :lock: | 1 | 05.06.2024 |
| 105 | 5.03448336.dat | [1JWXHwtBuVGDDjrVDQNFaBHhw7AhuuPeV9](https://www.blockchain.com/btc/address/1JWXHwtBuVGDDjrVDQNFaBHhw7AhuuPeV9) | 50% | :lock: | 1 | 05.06.2024 |
| 106 | 4.85582600.dat | [1JugtVnWfsRQB53woJCkKkLkL1HzHgXPvB](https://www.blockchain.com/btc/address/1JugtVnWfsRQB53woJCkKkLkL1HzHgXPvB) | 50% | :lock: | 1 | 05.06.2024 |
| 107 | 4.82537042.dat | [1Hrbgj881yoMYYvNvPkgGgEx6Kw8JxirLK](https://www.blockchain.com/btc/address/1Hrbgj881yoMYYvNvPkgGgEx6Kw8JxirLK) | 50% | :lock: | 1 | 05.06.2024 |
| 108 | 4.38100000.dat | [1CQyjZ8Rptd9YnZW7rX87rmni8HAPfwRgh](https://www.blockchain.com/btc/address/1CQyjZ8Rptd9YnZW7rX87rmni8HAPfwRgh) | 50% | :lock: | 3 | 05.06.2024 |
| 109 | 4.36000000.dat | [18Sb5pxmK7HNwG9dUrZhzzcAoX1n8FEUBu](https://www.blockchain.com/btc/address/18Sb5pxmK7HNwG9dUrZhzzcAoX1n8FEUBu) | 50% | :lock: | 1 | 05.06.2024 |
| 110 | 4.02219444.dat | [1L42VCpdoysXAstA9Ay4Q5V3QsK12grQ7H](https://www.blockchain.com/btc/address/1L42VCpdoysXAstA9Ay4Q5V3QsK12grQ7H) | 50% | :lock: | 1 | 05.06.2024 |
| 111 | 4.00043606.dat | [19sCR19UAdxCVPj6ATMGJV71J43X1wQoDa](https://www.blockchain.com/btc/address/19sCR19UAdxCVPj6ATMGJV71J43X1wQoDa) | 50% | :lock: | 1 | 05.06.2024 |
| 112 | 3.98999976.dat | [179ubgmB4sTRQSutRMovStFoAHxfoVnDK5](https://www.blockchain.com/btc/address/179ubgmB4sTRQSutRMovStFoAHxfoVnDK5) | 50% | :lock: | 3 | 05.06.2024 |
| 113 | 3.88501921.dat | [1DGNFJ6i4wvTAafLNux67w598bKREF5LwY](https://www.blockchain.com/btc/address/1DGNFJ6i4wvTAafLNux67w598bKREF5LwY) | 50% | :lock: | 3 | 05.06.2024 |
| 114 | 3.85090000.dat | [1GGwxGLy8PK1LUKBY71AZGessdkgdHxCd7](https://www.blockchain.com/btc/address/1GGwxGLy8PK1LUKBY71AZGessdkgdHxCd7) | 50% | :lock: | 1 | 05.06.2024 |
| 115 | 3.73979441.dat | [17KwpmAu27ycGndUU4Jwj2HvFkYEUefuJd](https://www.blockchain.com/btc/address/17KwpmAu27ycGndUU4Jwj2HvFkYEUefuJd) | 50% | :lock: | 1 | 05.06.2024 |
| 116 | 3.53383248.dat | [1NUW3z5z6cNs8Ltd2cN2BnxP92dySdcuG8](https://www.blockchain.com/btc/address/1NUW3z5z6cNs8Ltd2cN2BnxP92dySdcuG8) | 50% | :lock: | 4 | 05.06.2024 |
| 117 | 3.36894140.dat | [1BGJWEmGZhCYQEgp3pSZsBP3EYZF2c7vtS](https://www.blockchain.com/btc/address/1BGJWEmGZhCYQEgp3pSZsBP3EYZF2c7vtS) | 50% | :lock: | 1 | 05.06.2024 |
| 118 | 3.17460240.dat | [15NtoCW4eoT2L9LQRvpKtNdiHt3Lh1Sv9t](https://www.blockchain.com/btc/address/15NtoCW4eoT2L9LQRvpKtNdiHt3Lh1Sv9t) | 50% | :lock: | 1 | 05.06.2024 |
| 119 | 3.08715076.dat | [15tzMWqPk6XcW7g1AB2sLfHp8KAuzVkWBv](https://www.blockchain.com/btc/address/15tzMWqPk6XcW7g1AB2sLfHp8KAuzVkWBv) | 50% | :lock: | 1 | 05.06.2024 |
| 120 | 3.02000000.dat | [1ADuSfQpcGxQxZ22JATwdbDjxgDJHTpZ8N](https://www.blockchain.com/btc/address/1ADuSfQpcGxQxZ22JATwdbDjxgDJHTpZ8N) | 50% | :lock: | 1 | 05.06.2024 |
| 121 | 3.01244000.dat | [1L6HgRR5rJAUXb6UGK2Cu8ATLq48YRksTE](https://www.blockchain.com/btc/address/1L6HgRR5rJAUXb6UGK2Cu8ATLq48YRksTE) | 50% | :lock: | 1 | 05.06.2024 |
| 122 | 2.97000000.dat | [18cC6RJjYq5vxPAPmMA1KfszMzRr5FohLW](https://www.blockchain.com/btc/address/18cC6RJjYq5vxPAPmMA1KfszMzRr5FohLW) | 50% | :lock: | 1 | 05.06.2024 |
| 123 | 2.97000000-2.dat | [18cC6RJjYq5vxPAPmMA1KfszMzRr5FohLW](https://www.blockchain.com/btc/address/18cC6RJjYq5vxPAPmMA1KfszMzRr5FohLW) | 50% | :lock: | 1 | 05.06.2024 |
| 124 | 2.96812861.dat | [1Cr1cDL6NNzyWey66Lzt9QvCjKJXZgEs2p](https://www.blockchain.com/btc/address/1Cr1cDL6NNzyWey66Lzt9QvCjKJXZgEs2p) | 50% | :lock: | 1 | 05.06.2024 |
| 125 | 2.82717743.dat | [1PXJMEw2He6ESDJZkSzUA3eBD6XfCFrTna](https://www.blockchain.com/btc/address/1PXJMEw2He6ESDJZkSzUA3eBD6XfCFrTna) | 50% | :lock: | 1 | 05.06.2024 |
| 126 | 2.74500000.dat | [1Ea2zY7BZtLKmcT83QXscXcBudWATcSf7v](https://www.blockchain.com/btc/address/1Ea2zY7BZtLKmcT83QXscXcBudWATcSf7v) | 50% | 🔓 | 1 | 05.06.2024 |
| 127 | 2.74000000.dat | [1E1nwBt5yf71VpHDhbbiWKkGPrVV5ZwhXA](https://www.blockchain.com/btc/address/1E1nwBt5yf71VpHDhbbiWKkGPrVV5ZwhXA) | 50% | :lock: | 1 | 05.06.2024 |
| 128 | 2.73000000.dat | [1K3wtJsN8pkHB61EWfFy5VKD1dk6UNpMLy](https://www.blockchain.com/btc/address/1K3wtJsN8pkHB61EWfFy5VKD1dk6UNpMLy) | 50% | :lock: | 1 | 05.06.2024 |
| 129 | 2.69500000.dat | [1AZZbKaYZns8LAGnVdPQEShMzVKxcCMCfx](https://www.blockchain.com/btc/address/1AZZbKaYZns8LAGnVdPQEShMzVKxcCMCfx) | 50% | :lock: | 1 | 05.06.2024 |
| 130 | 2.68753118.dat | [1A2FEmGPFJrUMhCXwxhMriK7KFR7ivpwQZ](https://www.blockchain.com/btc/address/1A2FEmGPFJrUMhCXwxhMriK7KFR7ivpwQZ) | 50% | :lock: | 1 | 05.06.2024 |
| 131 | 2.63049301.dat | [13EmuvWVN7phTS5o9Ru1FsYuZ43rKpGTKm](https://www.blockchain.com/btc/address/13EmuvWVN7phTS5o9Ru1FsYuZ43rKpGTKm) | 50% | :lock: | 4 | 05.06.2024 |
| 132 | 2.53794900.dat | [16ySdKvgp9bHPgjnfxUawPrmRyQBvfbuWr](https://www.blockchain.com/btc/address/16ySdKvgp9bHPgjnfxUawPrmRyQBvfbuWr) | 50% | :lock: | 1 | 05.06.2024 |
| 133 | 2.50000000.dat | [1GGtCHaMAzSex7tRaNPMG1ZC2WF5UYuZjy](https://www.blockchain.com/btc/address/1GGtCHaMAzSex7tRaNPMG1ZC2WF5UYuZjy) | 50% | 🔓 | 1 | 05.06.2024 |
| 134 | 2.40000000.dat | [1AFuqjnZSveYPpaAQqH6VRssxSF9YjRxaz](https://www.blockchain.com/btc/address/1AFuqjnZSveYPpaAQqH6VRssxSF9YjRxaz) | 50% | :lock: | 1 | 05.06.2024 |
| 135 | 2.29597675.dat | [13Rb4ZMRjrkSYFLgdCJuxF7AWPngyaeC7e](https://www.blockchain.com/btc/address/13Rb4ZMRjrkSYFLgdCJuxF7AWPngyaeC7e) | 50% | :lock: | 1 | 05.06.2024 |
| 136 | 2.28883133.dat | [1FcHtQuvWrFLzqRKVgaaGHMEzL1o9bb36U](https://www.blockchain.com/btc/address/1FcHtQuvWrFLzqRKVgaaGHMEzL1o9bb36U) | 50% | :lock: | 1 | 05.06.2024 |
| 137 | 2.28384400.dat | [1CunakLPvMN4hHQzM5najUmQx2q2h8Mynv](https://www.blockchain.com/btc/address/1CunakLPvMN4hHQzM5najUmQx2q2h8Mynv) | 50% | :lock: | 1 | 05.06.2024 |
| 138 | 2.20704746.dat | [1N8L17Z7D6bBCWkSKABDf2qqJNHT1R9fv7](https://www.blockchain.com/btc/address/1N8L17Z7D6bBCWkSKABDf2qqJNHT1R9fv7) | 50% | :lock: | 1 | 05.06.2024 |
| 139 | 2.16000000.dat | [14R9c6qy3ES2YrdPhnDuncrJmqcFNdwUK8](https://www.blockchain.com/btc/address/14R9c6qy3ES2YrdPhnDuncrJmqcFNdwUK8) | 50% | :lock: | 3 | 05.06.2024 |
| 140 | 2.08763448.dat | [1JYfyscMaVHhSpqkU5mH5dFBz48etu6NPm](https://www.blockchain.com/btc/address/1JYfyscMaVHhSpqkU5mH5dFBz48etu6NPm) | 50% | :lock: | 1 | 05.06.2024 |
| 141 | 2.05917246.dat | [13A4wCqU2v5f1rMELgaJ1PV7CYD9yYPfQn](https://www.blockchain.com/btc/address/13A4wCqU2v5f1rMELgaJ1PV7CYD9yYPfQn) | 50% | :lock: | 1 | 05.06.2024 |
| 142 | 2.05423471.dat | [13TTA7LS3fvCRtUytEmW1HZwzY3kaahDqU](https://www.blockchain.com/btc/address/13TTA7LS3fvCRtUytEmW1HZwzY3kaahDqU) | 50% | :lock: | 4 | 05.06.2024 |
| 143 | 2.04866236.dat | [1QAZ3GbyK2bpuejqmoqQaveqoBDFjiY2Ds](https://www.blockchain.com/btc/address/1QAZ3GbyK2bpuejqmoqQaveqoBDFjiY2Ds) | 50% | :lock: | 1 | 05.06.2024 |
| 144 | 2.03000003.dat | [1GXR9FzCReefMfr1cWn2vFVqb7qsajTKxs](https://www.blockchain.com/btc/address/1GXR9FzCReefMfr1cWn2vFVqb7qsajTKxs) | 50% | :lock: | 1 | 05.06.2024 |
| 145 | 2.00792223.dat | [1Foen6hijntavxrwq6dC1sFKev6NYA4bbc](https://www.blockchain.com/btc/address/1Foen6hijntavxrwq6dC1sFKev6NYA4bbc) | 50% | :lock: | 3 | 05.06.2024 |
| 146 | 2.00515494.dat | [179F4iZspgdqy8Ugtw3z7wDu1kF3z1i4MG](https://www.blockchain.com/btc/address/179F4iZspgdqy8Ugtw3z7wDu1kF3z1i4MG) | 50% | :lock: | 1 | 05.06.2024 |
| 147 | 2.00000000.dat | [1NyAYbSvrx8T1YkwqnKQ6JZkTeKHcB4Les](https://www.blockchain.com/btc/address/1NyAYbSvrx8T1YkwqnKQ6JZkTeKHcB4Les) | 50% | :lock: | 1 | 05.06.2024 |
| 148 | 1.92980000.dat | [1BpehDQS3JHQmH3p8y1PrG6sycJ8S4z677](https://www.blockchain.com/btc/address/1BpehDQS3JHQmH3p8y1PrG6sycJ8S4z677) | 50% | :lock: | 1 | 05.06.2024 |
| 149 | 1.84950000.dat | [173qP26Urf7F3oJkEexfetTDjD4Y78fbjH](https://www.blockchain.com/btc/address/173qP26Urf7F3oJkEexfetTDjD4Y78fbjH) | 50% | :lock: | 1 | 05.06.2024 |
| 150 | 1.83949995.dat | [18jXjhpdiwF6R5YkPyUZMNSkxHRXEajYEq](https://www.blockchain.com/btc/address/18jXjhpdiwF6R5YkPyUZMNSkxHRXEajYEq) | 50% | :lock: | 1 | 05.06.2024 |
| 151 | 1.83913928.dat | [16pYs9RdquncSfqgVE1jARQhaLtURYnsng](https://www.blockchain.com/btc/address/16pYs9RdquncSfqgVE1jARQhaLtURYnsng) | 50% | :lock: | 1 | 05.06.2024 |
| 152 | 1.71600020.dat | [1PEbNwPneV4zs25tGEtXai38R9DX7Ly9mq](https://www.blockchain.com/btc/address/1PEbNwPneV4zs25tGEtXai38R9DX7Ly9mq) | 50% | :lock: | 1 | 05.06.2024 |
| 153 | 1.65000000.dat | [19agCPKUC8eD24W6AhrwSNwrUFtrr358vQ](https://www.blockchain.com/btc/address/19agCPKUC8eD24W6AhrwSNwrUFtrr358vQ) | 50% | :lock: | 1 | 05.06.2024 |
| 154 | 1.56079001.dat | [1CyiqmkPFb7SysXhhTdtd8ajpz58t5xFRY](https://www.blockchain.com/btc/address/1CyiqmkPFb7SysXhhTdtd8ajpz58t5xFRY) | 50% | 🔓 | 3 | 05.06.2024 |
| 155 | 1.44138096.dat | [17YbJhRweKx2tVqepkvMYKvP9zxLfXLKoz](https://www.blockchain.com/btc/address/17YbJhRweKx2tVqepkvMYKvP9zxLfXLKoz) | 50% | :lock: | 1 | 05.06.2024 |
| 156 | 1.44124101.dat | [1Lc6RJEB99cXMRBnkuTZqqojv6pRjikCkA](https://www.blockchain.com/btc/address/1Lc6RJEB99cXMRBnkuTZqqojv6pRjikCkA) | 50% | :lock: | 1 | 05.06.2024 |
| 157 | 1.39498354.dat | [1CcnHNGyxM6FCfjMrV5dwBW1mngGnUkFMF](https://www.blockchain.com/btc/address/1CcnHNGyxM6FCfjMrV5dwBW1mngGnUkFMF) | 50% | :lock: | 1 | 05.06.2024 |
| 158 | 1.09479390.dat | [1AS8nsUcQYvJQJDrxi9rpjSHa5n9hVLLno](https://www.blockchain.com/btc/address/1AS8nsUcQYvJQJDrxi9rpjSHa5n9hVLLno) | 50% | :lock: | 1 | 05.06.2024 |
| 159 | 1.08795916.dat | [1F654t1HxrZtg7uhcXyZeFvRsyB8HCnBXJ](https://www.blockchain.com/btc/address/1F654t1HxrZtg7uhcXyZeFvRsyB8HCnBXJ) | 50% | :lock: | 3 | 05.06.2024 |
| 160 | 1.00103254.dat | [1AxhH9CKkP1WBoT9bF1jFQo2nEdPDooP4i](https://www.blockchain.com/btc/address/1AxhH9CKkP1WBoT9bF1jFQo2nEdPDooP4i) | 50% | :lock: | 1 | 05.06.2024 |
| 161 | 0.92387567.dat | [19wCFh3wAqqWE9SNJu6QyBmCVX68zVGLH5](https://www.blockchain.com/btc/address/19wCFh3wAqqWE9SNJu6QyBmCVX68zVGLH5) | 50% | :lock: | 1 | 05.06.2024 |
| 162 | 0.53970361.dat | [1MJ5ebhcgZczc5qvdJM3h5SNYgUjDxjWeD](https://www.blockchain.com/btc/address/1MJ5ebhcgZczc5qvdJM3h5SNYgUjDxjWeD) | 50% | :lock: | 1 | 05.06.2024 |
| 163 | 0.39370194.dat | [1JQLXZdb19UcW2z6m3FzNUbVRKTU8ke7MV](https://www.blockchain.com/btc/address/1JQLXZdb19UcW2z6m3FzNUbVRKTU8ke7MV) | 50% | :lock: | 1 | 05.06.2024 |
| 164 | 0.36688060.dat | [1AaB2jXukNRcY88ichcuSvwvgKkNdWaNPC](https://www.blockchain.com/btc/address/1AaB2jXukNRcY88ichcuSvwvgKkNdWaNPC) | 50% | :lock: | 1 | 05.06.2024 |
| 165 | 0.29957903.dat | [1Fd4kGGuBwxH2QZe6cTS5GATXQeFBMmxKJ](https://www.blockchain.com/btc/address/1Fd4kGGuBwxH2QZe6cTS5GATXQeFBMmxKJ) | 50% | :lock: | 4 | 05.06.2024 |
| 166 | 0.21966138.dat | [1KVBdT8ypyywuisonw6k69UUynARJ366JW](https://www.blockchain.com/btc/address/1KVBdT8ypyywuisonw6k69UUynARJ366JW) | 50% | :lock: | 1 | 05.06.2024 |
| 167 | 0.10000000.dat | [1DH3GZaGLbgFvVPP9NzZDZXQweKhU2BHeG](https://www.blockchain.com/btc/address/1DH3GZaGLbgFvVPP9NzZDZXQweKhU2BHeG) | 50% | :lock: | 1 | 05.06.2024 |
| 168 | 0.07394004.dat | [12vdxXV3m5xRTi6vAAwMkQQkVL5rh9LESE](https://www.blockchain.com/btc/address/12vdxXV3m5xRTi6vAAwMkQQkVL5rh9LESE) | 50% | :lock: | 3 | 05.06.2024 |
| 169 | 0.06271293.dat | [15zrzE1psJJGjXyPiLkLTbiqwcjvE4hu7d](https://www.blockchain.com/btc/address/15zrzE1psJJGjXyPiLkLTbiqwcjvE4hu7d) | 50% | :lock: | 1 | 05.06.2024 |
| 170 | 0.05847536.dat | [19bdmxEtNgt1ogTWCYpGW2Qpn4qBmfUnGk](https://www.blockchain.com/btc/address/19bdmxEtNgt1ogTWCYpGW2Qpn4qBmfUnGk) | 50% | :lock: | 1 | 05.06.2024 |
| 171 | 0.04157575.dat | [1EjMaPCv4EyEVXWtWyPSD7HjAb4nZ9iADK](https://www.blockchain.com/btc/address/1EjMaPCv4EyEVXWtWyPSD7HjAb4nZ9iADK) | 50% | :lock: | 1 | 05.06.2024 |
| 172 | 0.02994543.dat | [1JsUStZoy9aHqFkH3Gqpz4RQFCFqyhk5W7](https://www.blockchain.com/btc/address/1JsUStZoy9aHqFkH3Gqpz4RQFCFqyhk5W7) | 50% | :lock: | 1 | 05.06.2024 |
| 173 | 0.01786378.dat | [12d31NMtE18xgdRLdhDgDs7BSSXxsZaH8r](https://www.blockchain.com/btc/address/12d31NMtE18xgdRLdhDgDs7BSSXxsZaH8r) | 50% | :lock: | 3 | 05.06.2024 |
| 174 | 0.01649536.dat | [16euRht9j5pysEQ8GSyqvWQWSVL9zmBvf6](https://www.blockchain.com/btc/address/16euRht9j5pysEQ8GSyqvWQWSVL9zmBvf6) | 50% | :lock: | 1 | 05.06.2024 |
| 175 | 0.01630413.dat | [1CxKn8H3tbo7s7qzExVD3eFs94nceNiiRV](https://www.blockchain.com/btc/address/1CxKn8H3tbo7s7qzExVD3eFs94nceNiiRV) | 50% | :lock: | 1 | 05.06.2024 |
| 176 | 0.01212207.dat | [1HQ3Go3ggs8pFnXuHVHRytPCq5fGG8Hbhx](https://www.blockchain.com/btc/address/1HQ3Go3ggs8pFnXuHVHRytPCq5fGG8Hbhx) | 50% | :lock: | 1 | 05.06.2024 |
| 177 | 0.01000000.dat | [18MW7RLHthpRDmzcfDjFSaTamxNSSkMs67](https://www.blockchain.com/btc/address/18MW7RLHthpRDmzcfDjFSaTamxNSSkMs67) | 50% | :lock: | 1 | 05.06.2024 |
| 178 | 0.00900000.dat | [16PCQnhRNZoD2jGuCNvfJS3aCZeELsX34A](https://www.blockchain.com/btc/address/16PCQnhRNZoD2jGuCNvfJS3aCZeELsX34A) | 50% | :lock: | 1 | 05.06.2024 |
| 179 | 0.00122539.dat | [15KeSdnNDVrCQ62TGFRNEx3xedKwXMpvn5](https://www.blockchain.com/btc/address/15KeSdnNDVrCQ62TGFRNEx3xedKwXMpvn5) | 50% | :lock: | 1 | 05.06.2024 |
| 180 | 0.00044000.dat | [1745e6GxkbEjsL28b9qpSHQKGBpWxFtQsD](https://www.blockchain.com/btc/address/1745e6GxkbEjsL28b9qpSHQKGBpWxFtQsD) | 50% | :lock: | 4 | 05.06.2024 |
| 181 | 0.00000580.dat | [17bqkPW21QhRUBcUQiy3C99ZC6L52Utu1b](https://www.blockchain.com/btc/address/17bqkPW21QhRUBcUQiy3C99ZC6L52Utu1b) | 50% | :lock: | 3 | 05.06.2024 |

## Heshes table

|  | Name  | Wallet password hash |
|:---|:---|:----------------------------------------------------------------------------------------|
| 1 | 10000.00417651.dat | $bitcoin$64$f0ef639cd01bb26805c190e0aeba006fbdd6b817e0b6634b0fb11944bc0f19eb$16$d2542bb38e0ee061$76753$2$00$2$00 |
| 2 | 5000.01168565.dat | $bitcoin$64$ad50c8d3435f8f711f384090a3df9112e0b84a0c97f727b3bbbdc28865d8d7b3$16$f193886b9f6d9853$37480$2$00$2$00 |
| 3 | 4000.dat | $bitcoin$64$ff4eb1d017921e0c7023da7e17aa72bd5f11f9025c844865665932125f79f465$16$6b8207637fc796a0$37698$2$00$2$00 |
| 4 | 4000.00222015.dat | $bitcoin$64$71e2e716521853a705f989b6095792e134a65d3c7dba4a2ef9e4b7b2a1b3b5c9$16$ad323db3a8d1a222$92592$2$00$2$00 |
| 5 | 478.33.dat | $bitcoin$64$2cc2bb488dc29fdfad85772b78bf96b29b054cd09a8a80311ebf6f7f821a8a63$16$c2ad95b0204070eb$67888$2$00$2$00 |
| 6 | 405.00120319.dat | $bitcoin$64$b56f1b90d107ee7e09e5f2ff6a430dbde219e17dfae7041b7b8eec3623b1a8ed$16$96846cdf25ec9168$36571$2$00$2$00 |
| 7 | 340.00283740.dat | $bitcoin$64$173aabf5927d86a1f9c34a59d9cd708c9d62fc181a90cf0f1b63e4b459981ac2$16$1d372be16c465eb6$131578$2$00$2$00 |
| 8 | 319.00053581.dat | $bitcoin$64$3e9bcabc966d7870f4ac263a2cb1efc2400644a917113c772375e588ecead5b1$16$18beed5b1565a5e5$47871$2$00$2$00 |
| 9 | 300.00055278.dat | $bitcoin$64$eace1c7e8662942150848fdbefbc83070bbc8c3a18d2c29b5132acb2c3f54f24$16$dd7d5c0aa12e709f$35211$2$00$2$00 |
| 10 | 252.20004225.dat | $bitcoin$64$13abcf57772b84ee6a219230be955924fe5da7d39218f0dba0be4656bed03e03$16$eea3cd87c0b59d6a$83164$2$00$2$00 |
| 11 | 200.00224825.dat | $bitcoin$64$8eb2f42013a2038debd86073f2927b6b06b5ea571e9dfa9a47850ee5d3d419ce$16$3671d4398b077fae$66889$2$00$2$00 |
| 12 | 198.00412439.dat | $bitcoin$64$a26662b81f90ae52c2e381b7b63c75325af6e46baf1c90621a885efe78178cc4$16$447b22ced4ef74c5$113073$2$00$2$00 |
| 13 | 186.29379209.dat | $bitcoin$64$f913fa9e5ea97dad615191c23af0f5ebdbe4693ddbea0903d9230832e7ae36c0$16$4cad32d55bbe6595$37167$2$00$2$00 |
| 14 | 180.77714198.dat | $bitcoin$64$47fcab2113982a4c02d852264e0803090ba0dfd25114164eba22470883ce4ebb$16$4f19e7f51dc4aeaf$72580$2$00$2$00 |
| 15 | 177.74326390.dat | $bitcoin$64$16f32e8ac625bd85062124bdee0276b74795a535d299118559560cf2f15d332e$16$656dc3e22ca1a711$131578$2$00$2$00 |
| 16 | 159.89913129.dat | $bitcoin$64$b540b7774bb0d392ca2ea1a5156f3c4ce5bc4687001cb79b3378519603819b21$16$3581059576caf391$52162$2$00$2$00 |
| 17 | 131.63.dat | $bitcoin$64$cace7ac50d843272b6e9ec834ac9a85bf1fa71176423ec780848d099d5856746$16$f61f668243cb1ca5$127854$2$00$2$00 |
| 18 | 130.00000547.dat | $bitcoin$64$2a7561ff817d54d524be0a9f19862403f015931a970cefb61f8f674b16e965a4$16$d09282a6c54e9d5f$83844$2$00$2$00 |
| 19 | 129.66226125.dat | $bitcoin$64$6bb4314c09ae8bc0ed3bb430509358f3455653d4554fe8f607c3bc98432cfeb9$16$d659cc9c4ee162e2$64397$2$00$2$00 |
| 20 | 108.06001094.dat | $bitcoin$64$e028fcb19d419b301a45f9850b750ad1ceaa8db1967b9fb8bbc4456ed5de580a$16$cf373e94a48bdb1f$35714$2$00$2$00 |
| 21 | 108.06001094-2.dat | $bitcoin$64$3e04675fd0e35dfee9ffb5cd55bed9903137b9f049406be43d04069c2fe96e9f$16$2aabeaeb7f4a1041$132242$2$00$2$00 |
| 22 | 105.11031599.dat | $bitcoin$64$6fe4843548d07f8aae5dafd4637d492243f60306028d5c7bc5ac56a2f57ccb54$16$99ac4b568568fb99$69345$2$00$2$00 |
| 23 | 99.99901094.dat | $bitcoin$64$08a4bbd5fbd998e5a334cb31dc43c3a625872998b6ff5b3830f5ffe30ee8156b$16$0af493ab2796f208$73689$2$00$2$00 |
| 24 | 91.00501641.dat | $bitcoin$64$e5f72c841730fd7e6965cb5c415016aa48c69757bcdf8c922a809d50af4c6c06$16$eddeaee1261a64e0$47530$2$00$2$00 |
| 25 | 90.59781094.dat | $bitcoin$64$eb22cf4ac8e7c5231096f7ce560803116345ba6cb0104f1488803e57f1d18e5c$16$8c0643774dcd2e5a$68452$2$00$2$00 |
| 26 | 87.86507229.dat | $bitcoin$64$0d79241a6ba712a0d55440104d01811ccdf4d4294bdd89748bbbb6ef46dc15d7$16$646ff236cc6fe1e9$83181$2$00$2$00 |
| 27 | 78.65929782.dat | $bitcoin$64$9e8d5b70d45f8fdeded358b8f72f81c0436398a220081a60044dc7bf5f9ea23e$16$cb9c55df52aa906e$35714$2$00$2$00 |
| 28 | 78.60361094.dat | $bitcoin$64$feb27bbab8b0a6f15b26f418c10a20bb73ba287d439ae5ab6ceb0287e731f55a$16$0af493ab2796f208$73689$2$00$2$00 |
| 29 | 77.98600547.dat | $bitcoin$64$528c67300053686ddcc5bde2ab6cd7dfa451a56e9c08aa27dcf1cc276cb3df48$16$8be30851d53f2928$40948$2$00$2$00 |
| 30 | 74.16883731.dat | $bitcoin$64$f8e443e6d6491d625a2ea48ddacffe0d1312ee59d80849d7f8cdb94d09931e84$16$7036c30511f8672b$36571$2$00$2$00 |
| 31 | 73.50781094.dat | $bitcoin$64$eb22cf4ac8e7c5231096f7ce560803116345ba6cb0104f1488803e57f1d18e5c$16$8c0643774dcd2e5a$68452$2$00$2$00 |
| 32 | 70.01000000.dat | $bitcoin$64$6b45588e745d8490f2432c68533407e0f2040ff12debd840270f47543ad47c16$16$0af493ab2796f208$99974$2$00$2$00 |
| 33 | 52.55001760.dat | $bitcoin$64$a0af3fa5006030e0edce5bf0931bebe7e0b27a694d314a68790d21347d79a657$16$2142112a50c1e140$73529$2$00$2$00 |
| 34 | 52.08001094.dat | $bitcoin$64$b1ed5af135a124b3041d79bb43074ae1054d3476693194d55d59c70252df19d6$16$aea459993c7600fe$38193$2$00$2$00 |
| 35 | 50.43201094.dat | $bitcoin$64$b4ec55497c544b4e6a7435fb6f30205c2baf86c9f533da2bbfa1e6f9fabdf330$16$3795a68bc27c5915$35537$2$00$2$00 |
| 36 | 50.18338758.dat | $bitcoin$64$f3c90b573111e06ff0f96ebf32921f5f3dd10ba219f391ab0fcc1adadd3e2000$16$9809070f76fa92c4$60692$2$00$2$00 |
| 37 | 50.00011641.dat | $bitcoin$64$25e8624d377949f36c4fdf104fa7f3ad3307be3499e72cae367f161b38a062d3$16$9d2eb2ad3e972053$37167$2$00$2$00 |
| 38 | 50.00004046.dat | $bitcoin$64$e5cd19531bbb0c546f510338013f8455b5cd9b2ed802b056847e88a8d1e391e8$16$eba14dbeb5c79b04$63443$2$00$2$00 |
| 39 | 50.00003282.dat | $bitcoin$64$3335c9e0dfd882b72d86f2b0412463e185768576771c6489e6fad6e4caec94c7$16$3365bac0544c6cc0$37167$2$00$2$00 |
| 40 | 50.00002188.dat | $bitcoin$64$f95b995bd952613281a7fbf16a37abfa342d579a651d2fcf32c21d7479fe587e$16$c61ebd84c4990e1f$70312$2$00$2$00 |
| 41 | 50.00001641.dat | $bitcoin$64$29ce72e5f11715f757021bc614fc29ec759cc614052d877ab050888f50245f82$16$2f756cb410d49abc$68432$2$00$2$00 |
| 42 | 50.00001641-2.dat | $bitcoin$64$3a454c193072c1c905d0d502adfee1e397e5795a5b7b476c15183f13d9c43e30$16$fdd4199dc3488f7e$61570$2$00$2$00 |
| 43 | 50.00000547.dat | $bitcoin$64$45abd6ebb0035af6c4ca2045a2bce9f663b763dc8afb558326752011ee85aa68$16$21eb684dadd49089$70727$2$00$2$00 |
| 44 | 48.92440002.dat | $bitcoin$64$f011045b52a39829f0e053f35b594c18c02bbcd936994279201cbd8e07f27197$16$b7445bc82d7e62fa$38043$2$00$2$00 |
| 45 | 42.53718329.dat | $bitcoin$64$b5ee3fb4fdb69a11efa972937e2fd0cf10c749b3d0967947205b4710f89fdbb3$16$00878c494362d4ab$35714$2$00$2$00 |
| 46 | 32.85679433.dat | $bitcoin$64$8ff0c52d3026ac8b949fdc64444d4daecbde19f8bfb3fb4b3e199fdb5aff8339$16$b5ba03e404f1d79d$125631$2$00$2$00 |
| 47 | 31.63000580.dat | $bitcoin$64$cace7ac50d843272b6e9ec834ac9a85bf1fa71176423ec780848d099d5856746$16$f61f668243cb1ca5$127854$2$00$2$00 |
| 48 | 31.01002188.dat | $bitcoin$64$bbd2f31a2bf33fcaea5d7f70f66cc1cf7273ba891ced76ced406bf762ee6bdba$16$4b495fa46139cf2f$132242$2$00$2$00 |
| 49 | 30.99098222.dat | $bitcoin$64$50bb9ef9cad87bf2b865b060e80c72c52f5ff496dbefa0bcfc6c3b5e0b86050e$16$f63cb4696e604d94$128289$2$00$2$00 |
| 50 | 28.00001000.dat | $bitcoin$64$3b5c5b0ddeebeb5697ab53e08b3a33073c51c2c1a93ce853ba7bc4a066d13b78$16$eba14dbeb5c79b04$37480$2$00$2$00 |
| 51 | 27.03768216.dat | $bitcoin$64$023ebec32970c6ec9453b84cea7bc58e92240534408cc6ea4a22cff2c21d0132$16$ef7b10ba55248b66$132242$2$00$2$00 |
| 52 | 25.99960547.dat | $bitcoin$64$c1f68299d421f5f2bba2947cc84bf1cd5be222b92db11473c25dd6f763ad40f1$16$57f4b89317e7d3ba$132242$2$00$2$00 |
| 53 | 25.00101641.dat | $bitcoin$64$144cc82f35ee18d502a01b826f5c47d201fad3167d26fe252595cf9c892584fa$16$af7ee951c6e05e80$33610$2$00$2$00 |
| 54 | 25.00011094.dat | $bitcoin$64$6b45588e745d8490f2432c68533407e0f2040ff12debd840270f47543ad47c16$16$0af493ab2796f208$99974$2$00$2$00 |
| 55 | 22.85001641.dat | $bitcoin$64$b5360e667fcdccf601d35c5f8bda852de40464373bb79df247c46ac6b97fa76e$16$8ead40334c7161b9$35714$2$00$2$00 |
| 56 | 21.89679859.dat | $bitcoin$64$4e5275fdaa62b805f8866082a87d953cca0c11e8e9d6511ab8a88690e107cd6d$16$802b35126a909e0f$81065$2$00$2$00 |
| 57 | 20.11001641.dat | $bitcoin$64$3e65e817d605b9d5d0b54bc8418a27aa104847dc59d664c6928601a8098927ee$16$5bcbad051d845552$60692$2$00$2$00 |
| 58 | 20.00241094.dat | $bitcoin$64$7120f443a02024283d9a4fef4c2c7167c2df239f4eeac4541a7327fab1ac05e0$16$88e39336106da6be$60692$2$00$2$00 |
| 59 | 19.88790000.dat | $bitcoin$64$a37dc249738892ddfee64fd9eef6a164c334b2828e24738f53bc22399f0f24a5$16$739dfbe436b4d196$38193$2$00$2$00 |
| 60 | 19.43300547.dat | $bitcoin$64$8109c279503278b8cdef8b67a817ab04c77c06dd7cc83b76fbe7f3d3f1d4f53d$16$5e4a6c017108845b$66056$2$00$2$00 |
| 61 | 19.33608000.dat | $bitcoin$64$f5a420086263fe96bf02389428e2a9bb043f52ecd0d09a15e99791e68153d98b$16$332e0d9db3c0ee6a$30841$2$00$2$00 |
| 62 | 19.30000000.dat | $bitcoin$64$9a7accab21442dd5c169eb408dc406c6cd77ccf39e9b3a1cf533bf867686c893$16$c7ee4cb0135cfabb$68810$2$00$2$00 |
| 63 | 19.28011668.dat | $bitcoin$64$f7ffc0d93ca4cef66464c5c5461889f5cbaa2bcfc09d2a01df216241d2e2be8e$16$1f1e4d7daa8cc4a1$67520$2$00$2$00 |
| 64 | 18.72704494.dat | $bitcoin$64$3662b157e4eecaf689bfc43252fba54d915592fd2332dd50128d61462f3dba64$16$a9cef4ffcfa6e71f$38193$2$00$2$00 |
| 65 | 18.17000000.dat | $bitcoin$64$27d8eb445a52382c6cfc18b49286087cf12db2e0ef12c77bd726a30cd72cb7ce$16$1d49acbff96eb626$35714$2$00$2$00 |
| 66 | 18.00000000.dat | $bitcoin$64$947f45d86f69bea47315abe26a0fd2eca5900909cb3d9fa47db36fab5584cccb$16$f04384fc94d2ba53$62973$2$00$2$00 |
| 67 | 17.82900000.dat | $bitcoin$64$1fdea045bad48f49950430d773df1f6be4220c6d97a4a0d5045a5b72835f5495$16$6c3755c8d7298b64$56081$2$00$2$00 |
| 68 | 17.82021465.dat | $bitcoin$64$64f7392c7fa156c85cc89d44edd6d27ddd0d68cb78a56a8ad60cd732fe569c01$16$2e7c23cc7fc0b14a$60692$2$00$2$00 |
| 69 | 17.20100000.dat | $bitcoin$64$8d167901e4f604a677eddb21460cddc4f5603f3b21ebe33ff726d9077ee07cdb$16$722cb04e0e8fa285$66170$2$00$2$00 |
| 70 | 17.19060793.dat | $bitcoin$64$54c20b76a774c8a9064e42d63ce98ae531b7c011483d25c42ad02ef0456aa376$16$e759f4549f41b949$77315$2$00$2$00 |
| 71 | 17.09000666.dat | $bitcoin$64$7f126bc43475c2fa85d7831a854d87a0ede3d742f6da71f79ccb65c284c6b0ba$16$fa85aa2d5eacee31$67271$2$00$2$00 |
| 72 | 17.08998980.dat | $bitcoin$64$0b7b5199cf24c104c1b130906774f2843d1f01ae62c8fff935c7afc3411dc8e9$16$66934f0863dd4482$63268$2$00$2$00 |
| 73 | 16.23030002.dat | $bitcoin$64$beee3a4519bd860e383f3a114b3a08cb4e7199248ea06d392fd9af52c042b4db$16$b6a4588ae3ba3e36$60714$2$00$2$00 |
| 74 | 16.13643422.dat | $bitcoin$64$00b0d3980bab3d9b3694fbed9e9082bd2fdf9b5ff8a4fd05b6599b556c6b1c67$16$22589d3f997c387f$60435$2$00$2$00 |
| 75 | 15.99100158.dat | $bitcoin$64$2ecb6691460c19de44584d2b22d201597874ec4ced76c806455e079e6d811da8$16$fbf192d3baf6bb02$126145$2$00$2$00 |
| 76 | 15.75044635.dat | $bitcoin$64$af049ff75a8d5c1214e252f3c926b7b63e20f78f07fd411ca04140f272e557ae$16$999bf4729b971c7e$67169$2$00$2$00 |
| 77 | 15.71719998.dat | $bitcoin$64$e1fcb6f24724b47a52bb16b9ac6a150454977541f44decb080c63471880e4c1c$16$012f4675057fd231$69491$2$00$2$00 |
| 78 | 15.01812238.dat | $bitcoin$64$0d620dd9913bb3d0993bc7626bd5b4f388b64440498c4da55b52d53ff2f2d161$16$73b40d780231b8ca$63056$2$00$2$00 |
| 79 | 14.77500000.dat | $bitcoin$64$0d620dd9913bb3d0993bc7626bd5b4f388b64440498c4da55b52d53ff2f2d161$16$73b40d780231b8ca$63056$2$00$2$00 |
| 80 | 14.70456309.dat | $bitcoin$64$5e8a31c248beb652f3403ebab417104a689e8c332c1b439dac8bb80fc92b762e$16$f6a2d85665fd5826$62954$2$00$2$00 |
| 81 | 14.60000000.dat | $bitcoin$64$44edd3d9e1aca5d3e486e2a43c3c507b475fd6d2235f91394bf96105e78105c9$16$0db9b5dd9f71ba20$61714$2$00$2$00 |
| 82 | 14.35226342.dat | $bitcoin$64$deed81af471f5677b7c11a883237b20c9e6b8738e5e65945f4288ece6f413a57$16$f0bdf179fd204a59$35211$2$00$2$00 |
| 83 | 14.09013974.dat | $bitcoin$64$f83d2783f238d5fde0e082e20686ff85cb92bb0737da214e2e39fd61b828bf6c$16$adfbb9cfa83e9cf6$135318$2$00$2$00 |
| 84 | 14.00010000.dat | $bitcoin$64$c00315444e82cc43ec23bea608c7889138a6d73bcdef3ae3526fb64ef79ab0e9$16$f8a9ac6e9be0c72e$74899$2$00$2$00 |
| 85 | 13.76858117.dat | $bitcoin$64$c4904a4e27e374a782aa9700bc953bea61dc0342f8df97491d229fc6bcd5c641$16$25b711ed92cdf3c3$74899$2$00$2$00 |
| 86 | 13.47094589.dat | $bitcoin$64$a056da8f6713a70d9f6b125931ac02a3b89f3aed658ab444b624c740d08460d2$16$ded7ea15fc0ad57c$53205$2$00$2$00 |
| 87 | 12.82192064.dat | $bitcoin$64$b111269df559c2c8929f4e7d82bd627317301d9fdd189b5360153ab28f7d04a0$16$cf488450374c34d5$35714$2$00$2$00 |
| 88 | 11.26827053.dat | $bitcoin$64$6b45588e745d8490f2432c68533407e0f2040ff12debd840270f47543ad47c16$16$0af493ab2796f208$99974$2$00$2$00 |
| 89 | 10.83091000.dat | $bitcoin$64$6942834a1cdda69705d2cf9ebc3a204d5bfa64ff40d81db0bac6ccf63b3aff8f$16$00aa7d8b96e6174d$37698$2$00$2$00 |
| 90 | 10.50200000.dat | $bitcoin$64$93112f8c11e9cbff7561038eddf268827dd38c72354695fc70d4a01102d22c48$16$14bff2455913f62c$25000$2$00$2$00 |
| 91 | 10.21000001.dat | $bitcoin$64$5c9d138da82ecbffde730616d3c2b55553118d3884342ac3ee36c9f0cbb552fd$16$3dab00ca419a9840$57197$2$00$2$00 |
| 92 | 8.90000000.dat | $bitcoin$64$fbb81fa5f31a282331e8ef06d849522e282bd6689174b970fd8635eff36887ca$16$d68a0ad1e3fdd725$71074$2$00$2$00 |
| 93 | 8.77089137.dat | $bitcoin$64$ef08500b11fda51111e9106ab0bc60fb77870202a7a433abe1dda820be9134f6$16$a962fdb86e3161a4$60692$2$00$2$00 |
| 94 | 8.50023481.dat | $bitcoin$64$ff134f9f03da571e5b256dec561730aaa674ff37d8a698d3c2c5e66fdbb07335$16$125d64b2bab4c437$136217$2$00$2$00 |
| 95 | 7.00000000.dat | $bitcoin$64$f20759bb3249e7f1928373981c4efb014d45b632ed8a3c781f061b92d095888b$16$3ff48fe3e092513b$111555$2$00$2$00 |
| 96 | 6.33718357.dat | $bitcoin$64$829c1c500a6b80ce0f6a622bf77d9ad75fc07abe2753695e8c256bdd5e5ad872$16$e88c5fd7136eb715$52082$2$00$2$00 |
| 97 | 6.33560000.dat | $bitcoin$64$6631eda4a5fbaf95d5d4fe18f9b04401fae84adbaf2238f78c1871dcadfde1a8$16$dbd7bd2153d79ff9$47334$2$00$2$00 |
| 98 | 6.29000000.dat | $bitcoin$64$df4579769ff97a92cb815f8484e16e796df133e84ff392d56eb65399b69be57a$16$5f3ced39d11972bc$77315$2$00$2$00 |
| 99 | 6.19445176.dat | $bitcoin$64$04ac3ea427bfa8ddb2c6e10199267cd338cc9b19e4e5ce0806f6078b312604bf$16$b09bc7e9b1c6087e$59659$2$00$2$00 |
| 100 | 6.00000000.dat | $bitcoin$64$cbd7fe1739ba5dbf965fa015bc4cb089649a56a9a0002b74ac0c1076bf81de40$16$2090fd216ae96fee$61090$2$00$2$00 |
| 101 | 5.89290000.dat | $bitcoin$64$1d94364372d1cae4bfacbc1ac7722c2bf92a98de47ec2f8ac476119d45d40a60$16$ca471cd3a19b04ff$67917$2$00$2$00 |
| 102 | 5.86332001.dat | $bitcoin$64$7095f9031c639640d11d86c0a8597556ae8c940fb3bbda7c1cd789c3fea8dc08$16$c738f48338155e0a$67219$2$00$2$00 |
| 103 | 5.08877624.dat | $bitcoin$64$aef813b23f8577f617d5d4890c1d769c46cb492e519214eb8d85c6f1606b6b3b$16$de2b3bd38f902753$64425$2$00$2$00 |
| 104 | 5.05538396.dat | $bitcoin$64$5b6312295d46f157526f818dd79e9caff8df36e7ae5977863ee6686d9b8069ff$16$e6405f8a7f5ae3c7$107430$2$00$2$00 |
| 105 | 5.03448336.dat | $bitcoin$64$6b45588e745d8490f2432c68533407e0f2040ff12debd840270f47543ad47c16$16$0af493ab2796f208$99974$2$00$2$00 |
| 106 | 4.85582600.dat | $bitcoin$64$41f22b8d40dc773fae1acacc0c10c5746e0bf8cac6cee1129ade3b3d49b99a9f$16$fef57fc288239116$130926$2$00$2$00 |
| 107 | 4.82537042.dat | $bitcoin$64$fd1efeee395b9f5167ef5b2d40e6701164bd8fda6f055b21161f0f6b214cfdc5$16$32ddd688dd623687$35714$2$00$2$00 |
| 108 | 4.38100000.dat | $bitcoin$64$0e7f3dd3368aa563848291d14059ca6b969fdc6567be670d93f982693c4a913b$16$df1b66a2e41c2eb3$35714$2$00$2$00 |
| 109 | 4.36000000.dat | $bitcoin$64$4e5275fdaa62b805f8866082a87d953cca0c11e8e9d6511ab8a88690e107cd6d$16$802b35126a909e0f$81065$2$00$2$00 |
| 110 | 4.02219444.dat | $bitcoin$64$b1aefb2665d35512c81f3765cd99d0a7cc1e15fcb741d0f21a46babaf9576cc1$16$6390ddc3df7fbd48$72463$2$00$2$00 |
| 111 | 4.00043606.dat | $bitcoin$64$bcbea16e815204542d0c5c933a9b4082e34ac2143b586c8084bc6519e340375e$16$df41a91be092cb86$64053$2$00$2$00 |
| 112 | 3.98999976.dat | $bitcoin$64$71fe0d4dc27b24dcd1ea6639d644e8daeff04c38e30d05f0a74b17d28f25667e$16$df6cabc03425d39a$35714$2$00$2$00 |
| 113 | 3.88501921.dat | $bitcoin$64$71fe0d4dc27b24dcd1ea6639d644e8daeff04c38e30d05f0a74b17d28f25667e$16$df6cabc03425d39a$35714$2$00$2$00 |
| 114 | 3.85090000.dat | $bitcoin$64$895b386376c1ca9c1f8b440ea269eb4a772bcb4b47757c7708a03fd47a8ca3f2$16$d1d93a887220a49f$31249$2$00$2$00 |
| 115 | 3.73979441.dat | $bitcoin$64$7c777ff6ca1be06757120c36eba39c7573a1154cf35277e4740f13b1b44504e4$16$24089973d01d5f0d$82925$2$00$2$00 |
| 116 | 3.53383248.dat | $bitcoin$64$011f6abdec8e23032b7eb1298ed661fb9ebcd7388b3963b527a2923cce6800ea$16$e4aa72cd2bfa00cd$68014$2$00$2$00 |
| 117 | 3.36894140.dat | $bitcoin$64$a1a3ef63fba5710a98208a9dffa57d64b2a2d69e475514a1ddd4d178bf04a171$16$4eb9d7607de381ac$71074$2$00$2$00 |
| 118 | 3.17460240.dat | $bitcoin$64$23ca949be014591b7d6084702e54aebdebe5ee3658d7cb45cb2cc502c17ccce2$16$e167a26aaf9a728e$67219$2$00$2$00 |
| 119 | 3.08715076.dat | $bitcoin$64$fbb855a7512b44a6c34c0e762c2844b1c5078a9bf175ccf894f6660660031ecd$16$b2703da18a5ac317$76979$2$00$2$00 |
| 120 | 3.02000000.dat | $bitcoin$64$70e4c5802b753c0a54bfaed48c660091ee646e86b313a37c7c4fa4b9552369dc$16$6cfd640bb735f660$31609$2$00$2$00 |
| 121 | 3.01244000.dat | $bitcoin$64$89cb146e3db70ae648d03266ab4f506e027b57137066c4d888ec66fbfde5236e$16$74752ca5389ef081$70054$2$00$2$00 |
| 122 | 2.97000000.dat | $bitcoin$64$0a5930326e7079600c75fd3bb4608727ee98888100322a4dbfdbe1f88e2e0b21$16$b4198b2d3fceaae7$61763$2$00$2$00 |
| 123 | 2.97000000-2.dat | $bitcoin$64$5188754f6b4942270d8f1dcaa8b1658b5e82fac953a7394dd8a5d0cf622ae70f$16$6cf03da04dc5b899$72580$2$00$2$00 |
| 124 | 2.96812861.dat | $bitcoin$64$63e3a2b4a51ab13427e0a1e728c903933e87e8621b7d681ad45c4bd025831975$16$cf56402c27786c22$69042$2$00$2$00 |
| 125 | 2.82717743.dat | $bitcoin$64$6d09cc1ed352f52f93ca0ee33a6b0350ce9f9ebfb0ebfcb88f5e41e708fd40c0$16$da73658aa029b6dd$47871$2$00$2$00 |
| 126 | 2.74500000.dat | $bitcoin$64$3c7561c0d8ed6700b7e1a48a94077f9595858f07e05fa51c4575e5a9785b9723$16$f93dd4c873efcf97$38657$2$00$2$00 |
| 127 | 2.74000000.dat | $bitcoin$64$0570ebd633691b97f566a8b73147d69723c94ad10b141f1c4d7e3c96bd408096$16$0f5ec00d429b9704$63835$2$00$2$00 |
| 128 | 2.73000000.dat | $bitcoin$64$8109c279503278b8cdef8b67a817ab04c77c06dd7cc83b76fbe7f3d3f1d4f53d$16$5e4a6c017108845b$66056$2$00$2$00 |
| 129 | 2.69500000.dat | $bitcoin$64$4d93553d15560f2e50533c3fd271fe41e1cf1baf9dbec1711746a21a42db05dd$16$f16dd4acd044b5c1$101546$2$00$2$00 |
| 130 | 2.68753118.dat | $bitcoin$64$b9d677fa8a11b6619cfedca40c837b0d3343ff20df48cf37700394b5b64cf192$16$a80e5f4352c4f324$71314$2$00$2$00 |
| 131 | 2.63049301.dat | $bitcoin$64$743fdef2fb02a380440324cfb90fc6dc4deb5e788063d10bf4708cd9e5a23265$16$9d004c2bee7de706$63894$2$00$2$00 |
| 132 | 2.53794900.dat | $bitcoin$64$2ce3118fd2a87834b49b63916edd4935d89e905c2bedf6c97f19ff466b299b65$16$9480b99863bc4940$38489$2$00$2$00 |
| 133 | 2.50000000.dat | $bitcoin$64$a64fe88a288fb7512b54d7dd64f9641fe2e70919f3c15c8dcc70a512aac166e6$16$dd272ec0ee200a78$77315$2$00$2$00 |
| 134 | 2.40000000.dat | $bitcoin$64$2f77476dd3fd9db01c9d645ea24ec05c5c8125166fc07bac4d8c147c2c84167d$16$35af01fbce5b5e5f$62313$2$00$2$00 |
| 135 | 2.29597675.dat | $bitcoin$64$fa7064fb38bd3ae262b2d88d4ba62b4870b23ff326ba14ba60de551fab7a9327$16$460f24cf3825a045$34090$2$00$2$00 |
| 136 | 2.28883133.dat | $bitcoin$64$534982bd75fd55de814558f847d48a8805300c9144b557b3f82cbac0ffc66398$16$f1f0b2aa64c3d426$37698$2$00$2$00 |
| 137 | 2.28384400.dat | $bitcoin$64$f7ffc0d93ca4cef66464c5c5461889f5cbaa2bcfc09d2a01df216241d2e2be8e$16$1f1e4d7daa8cc4a1$67520$2$00$2$00 |
| 138 | 2.20704746.dat | $bitcoin$64$8ff0c52d3026ac8b949fdc64444d4daecbde19f8bfb3fb4b3e199fdb5aff8339$16$b5ba03e404f1d79d$125631$2$00$2$00 |
| 139 | 2.16000000.dat | $bitcoin$64$bfda1e650f5324d5baf7e8436f0bf1982e2d454eca3cec181f85d573217a5f37$16$235a24fb9826bc63$38193$2$00$2$00 |
| 140 | 2.08763448.dat | $bitcoin$64$fa7064fb38bd3ae262b2d88d4ba62b4870b23ff326ba14ba60de551fab7a9327$16$460f24cf3825a045$34090$2$00$2$00 |
| 141 | 2.05917246.dat | $bitcoin$64$ec3edca5b3aff92ab10ac7681b05ee077681734dfad8b090dfefb969ec26eb4b$16$67201c141a44d1cd$36289$2$00$2$00 |
| 142 | 2.05423471.dat | $bitcoin$64$aac33eb84a63a97eacf895b3c38bddc2a0af250817aea7751740c2ec9a0df82f$16$cf1101986a7a95bb$61764$2$00$2$00 |
| 143 | 2.04866236.dat | $bitcoin$64$500cd102da82a708c81b68711faeb598210f30a0d601bb0e75c7464a4d3c20c2$16$f1fd68a3f791484b$61442$2$00$2$00 |
| 144 | 2.03000003.dat | $bitcoin$64$c71e083361cd16dfbf5acaa2d0af0532554e1fd6982f6e5341bc5a7d4886080f$16$d6283ab0e04e9b78$63852$2$00$2$00 |
| 145 | 2.00792223.dat | $bitcoin$64$64668bf6d05f12989ac6e9c290948a87a550b057dafc19e8e0647356b10075a6$16$803496cf5f4a82bc$37698$2$00$2$00 |
| 146 | 2.00515494.dat | $bitcoin$64$89cb146e3db70ae648d03266ab4f506e027b57137066c4d888ec66fbfde5236e$16$74752ca5389ef081$70054$2$00$2$00 |
| 147 | 2.00000000.dat | $bitcoin$64$7331cec5bbf44062c5488c40815cd2117da80b6e46bf56ad5142f126eb51b412$16$2fd37542ebc0cf7d$65866$2$00$2$00 |
| 148 | 1.92980000.dat | $bitcoin$64$6b180d8285ae3d5ab952950314df765615c5118393edfff5511f5419330a1d8e$16$1bd4e867b0f742b6$36208$2$00$2$00 |
| 149 | 1.84950000.dat | $bitcoin$64$bb99f6bca2f215c658848ff7ea1c9459e29bbfb17e2cde0ae0a4769edcee0107$16$68d7955607946058$41608$2$00$2$00 |
| 150 | 1.83949995.dat | $bitcoin$64$6bef8568c8f81f067586cb5579b9edbef942c1d87f441b82adc14fd399305880$16$e6753cf77fbccd3a$104326$2$00$2$00 |
| 151 | 1.83913928.dat | $bitcoin$64$c6c01dbdb35f65adfdf9ab423bb5cc1ac3b4b7969e65d37961272973e0c5e375$16$6bccd28adff9fc07$67908$2$00$2$00 |
| 152 | 1.71600020.dat | $bitcoin$64$cf855f694ea9768a421ea1c46d47cf2ca07c8a5003fa6b338dfa12d9d55b229a$16$ad22f110e67113a4$37698$2$00$2$00 |
| 153 | 1.65000000.dat | $bitcoin$64$cfd9ff763c32192562a8e2a80b2dc2454fd91c22a4896e5a4e4503df011eb299$16$0d0477aa5f576baf$60455$2$00$2$00 |
| 154 | 1.56079001.dat | $bitcoin$64$f01e1ef5f265eaaffa747fd13abbf4a6df16216ceb99d37d903e5638b5da0144$16$8422e687825ae181$37167$2$00$2$00 |
| 155 | 1.44138096.dat | $bitcoin$64$44ed889592a8d7b9bf6c8b1ed8bd676ca69a63c866e04f0119c34c1a7a185446$16$9e9ebf3cbd7605d8$64337$2$00$2$00 |
| 156 | 1.44124101.dat | $bitcoin$64$af049ff75a8d5c1214e252f3c926b7b63e20f78f07fd411ca04140f272e557ae$16$999bf4729b971c7e$67169$2$00$2$00 |
| 157 | 1.39498354.dat | $bitcoin$64$65f0d344dcd7181ec223746a84f42b620e550a1019742f495fd76b2578523330$16$d699839d9729686b$60211$2$00$2$00 |
| 158 | 1.09479390.dat | $bitcoin$64$51307c1824f9756c0542218c6c3054974e07dc5c58f8411173c12f7e938b5f10$16$0f088e5c4d1a0515$62055$2$00$2$00 |
| 159 | 1.08795916.dat | $bitcoin$64$9de529051d808b5d34c679c43020a233e6b5161de2e85070127009d61e4c24c8$16$09792b4786f368cb$49019$2$00$2$00 |
| 160 | 1.00103254.dat | $bitcoin$64$01f782c4a3a71e9da3af5f7fe3977f10e9216f239814a45148c0d58ea0b486bb$16$e0eb85213cc20ccc$65828$2$00$2$00 |
| 161 | 0.92387567.dat | $bitcoin$64$02fac009c7298c142c27aaf52a10b984bb578f124cb1ed0854fe460f16aa9cf4$16$1dabf1816b34e175$62719$2$00$2$00 |
| 162 | 0.53970361.dat | $bitcoin$64$9810cb6ab1782a996319de81ef4cba2f7b9c97fbb252fc49be3962377405799a$16$7f6fe559a2c604ba$36289$2$00$2$00 |
| 163 | 0.39370194.dat | $bitcoin$64$89a7fa8115d6dc6709a63ac2c23ea5e7887d995a470400e251a2a53fe83114ba$16$5bd305e281c14394$71788$2$00$2$00 |
| 164 | 0.36688060.dat | $bitcoin$64$28a5eff3231423506ac1e0775e941ffc261e60dd43978572ca9a515cb39072aa$16$d7a612453f69d549$56140$2$00$2$00 |
| 165 | 0.29957903.dat | $bitcoin$64$0aa56f47a5656a0913e1be368d72c232f6d7c7b1d99a340c7643c9366e232600$16$2c5962df398dcd25$74899$2$00$2$00 |
| 166 | 0.21966138.dat | $bitcoin$64$825aae165a699d1d4de7fe313ff3afbd7deb58802e0d6cc96da1b158ca6010a4$16$f3a81a82d737a22d$63054$2$00$2$00 |
| 167 | 0.10000000.dat | $bitcoin$64$c41baa1032a77683bf724234659b51eb1ed1b88fbd3a9620152fbce5a5a2c738$16$ed3c45fcc4ea0f06$103191$2$00$2$00 |
| 168 | 0.07394004.dat | $bitcoin$64$617c4b22fabd578e0f4d030245a0cbebd9da426fbee49c2feb885fa190b65096$16$dff2b89e4d885c28$35714$2$00$2$00 |
| 169 | 0.06271293.dat | $bitcoin$64$b79d2b59e3ea4e90a039aa29e7a13981ce0e452158a77fd8d92fe4b32dbf0b06$16$f8f9e047cbbc102a$54976$2$00$2$00 |
| 170 | 0.05847536.dat | $bitcoin$64$bcbeea02a2bb40ec99ad8b76d21616d829fdb425399e46094417475177f3981e$16$d37e85f7f94cc276$70517$2$00$2$00 |
| 171 | 0.04157575.dat | $bitcoin$64$da5d83d08330d95c09b39e7b938a79b2170f39b8abade5a08438bf3efc59578e$16$d98f9e1b60b753b5$50122$2$00$2$00 |
| 172 | 0.02994543.dat | $bitcoin$64$a5e6b2b8df29c92ea2eadbd8933517a8c6cbc4f1718f5cf663a994e149948c93$16$50214f4cacd91f84$68432$2$00$2$00 |
| 173 | 0.01786378.dat | $bitcoin$64$3420a7252f5ee93d31ef7734a56f93fd08e0e6ea7a4686e40f0e5e3e972fd6d5$16$885a0196aab916d0$193105$2$00$2$00 |
| 174 | 0.01649536.dat | $bitcoin$64$c186d4f68030949390af608519d5762a993158d655eb500cc23356324d46f9bb$16$8e75f5e20d006f95$74899$2$00$2$00 |
| 175 | 0.01630413.dat | $bitcoin$64$21c25dd14dd7bc7bad4c3fcd9629ee862e0b27307092f25d3e963d76ea5d472b$16$d7cd7e3809ef7edb$81717$2$00$2$00 |
| 176 | 0.01212207.dat | $bitcoin$64$1f72bf18ffa4fdc760635d8c13109da196d3dc802d5aabb23fa6c6aaba9a1dbb$16$04436c19f8b3699f$41162$2$00$2$00 |
| 177 | 0.01000000.dat | $bitcoin$64$3a34378f68fc6b07a19770a5c839450aa3bdc2b96535ec5937d32d70e2f11e72$16$6740187b4c919c9b$66355$2$00$2$00 |
| 178 | 0.00900000.dat | $bitcoin$64$92c8e00c8537624867d7aaff1a31abc72cf1b97cb923cf802aaab551e6f30623$16$cacbf690816bb4f6$76979$2$00$2$00 |
| 179 | 0.00122539.dat | $bitcoin$64$234bcceda74df69c8107ea28cb7dda04753a8bab324bfdb175d5552558c689c1$16$599c639c12d31797$70564$2$00$2$00 |
| 180 | 0.00044000.dat | $bitcoin$64$3a45a03d43e6e18b62a456df9a89bec08b5ab58db967a44a893e095d6d1ddcfb$16$b0ac9e8408ebe940$89166$2$00$2$00 |
| 181 | 0.00000580.dat | $bitcoin$64$9269f788d7bcecd411d95cc222c9f0cdf7ebfc6fa33847607f7b8c1338a2c3f8$16$10cb87989a39ef71$60692$2$00$2$00 |

## Frequently asked Questions
**Are your wallets real?**</br>

99% - YES</br>
Wallets were maximally checked for validity.</br>
Coins were sent to some dubious wallets for verification.</br>
There is no way to verify wallet.dat is 100%</br>
This can only be done if the correct password is entered.<hr>

**How do you have so many wallets?**</br>

Wallets were presented to me by various hunters for 25% of the amount of the find.</br>
Hunters received wallet.dat by exchanging with other hunters.<hr>

**Any passwords hints?**</br>

Maybe it's an email ?</br>
Possibly 12 capital letters ?</br>
Possibly word + word + 2011 ?</br>
They are not exact, come up with your own combinations<hr>

**If I find. What are the guarantees of paying me 50% ?**</br>

If you find the hash password.</br>
Write to me in telegram ```phrutis```</br>
After agreeing, and receiving your BTC address from you.</br>
Sending coins to 3 addresses will be prepared.</br>
Your address is 50% 1......?</br>
Partner address 25% (btc address from table)</br>
My address is 25% bc1qh2mvnf5fujg93mwl8pe688yucaw9sflmwsukz9</br>

A password will be required to confirm the transfer.</br>
I give you the id of a AnyDesk running Bitcoin core.</br>
You connect, you see the active bitcoin core what and where it is sent. </br>
Check your address, enter your password and click send transfer.</br>
So there will be a guarantee and security for all participants.</br>
The characters are hidden in the input window.</br>
An example of a screenshot of entering a password</br>
![pass](https://user-images.githubusercontent.com/82582647/171959020-8192f5ad-6d3c-4295-af77-8fe348769853.png)
<hr>

**I have an old wallet.dat (not from a table) want 25%**</br>

You can contact me in telegram ```phrutis```</br>
Provide me with the old wallet.dat</br>
After verification, it will be added to the table with your btc address.</br>
If hunters find password you will get 25%<hr>

**I have a wallet.dat with the same hex, there is a different amount, it's empty, it's a fake?**</br>

You may have an older version of wallet.dat</br>
There is a newer one in the challenge.</br>
In a later version, the user could add a new address and receive coins on it.</br>
The old version of wallet.dat does not have this address.</br>
Or vice versa.<hr>

**HiveOS Error during speed benchmark, return code: 137**</br>

Must either increase RAM or do a SwapFile</br>
```sudo fallocate -l 12G /swapfile && sudo chmod 600 /swapfile && sudo mkswap /swapfile && sudo swapon /swapfile && sudo cp /etc/fstab /etc/fstab.back && echo '/swapfile none swap sw 0 0' | sudo tee -a /etc/fstab```
<hr>

