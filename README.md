# @HACK 2025: AI Leaky ReLU

> Authored by [Hugo](https://github.com/hkerma).

- **Category**: `AI`
- **Value**: `300 points`
- **Tags**: `http`

> Man, I don't know that these engineers are trying to do, but we got access to their model's inference API. See if you can find what they use it for.
> 

## Files
- **[Download: app.py](https://github.com/athack-ctf/chall2025-ai-leaky-relu/raw/refs/heads/main/offline-artifacts/app.py)**
- **[Download: model.py](https://github.com/athack-ctf/chall2025-ai-leaky-relu/raw/refs/heads/main/offline-artifacts/model.py)**

## Access a dockerized instance

Run challenge container using docker compose
```
docker compose up -d
```
Open below URL on your browser
```
http://localhost:52001/
```
<details>
<summary>
How to stop/restart challenge?
</summary>

To stop the challenge run
```
docker compose stop
```
To restart the challenge run
```
docker compose restart
```

</details>


## Reveal Flag

Did you try solving this challenge?
<details>
<summary>
Yes
</summary>

Did you **REALLY** try solving this challenge?

<details>
<summary>
Yes, I promise!
</summary>

Flag: `ATHACKCTF{L0ngL1veOurL0rdAndS4vi0rptrblck}`

</details>
</details>


---

## About @HACK
[@HACK](https://athackctf.com/) is an annual CTF (Capture The Flag) competition hosted by [HEXPLOIT ALLIANCE](https://hexploit-alliance.com/) and [TECHNATION](https://technationcanada.ca/) at Concordia University in Montreal, Canada.

---
[Check more challenges from @HACK 2025](https://github.com/athack-ctf/AtHackCTF-2025-Challenges).