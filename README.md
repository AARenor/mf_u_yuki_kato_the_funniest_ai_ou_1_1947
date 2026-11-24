# Out-of-office reply

A small program that writes one short text — the funniest out-of-office auto-reply an AI agent can leave before vacation — for make.fun's bounty `u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d`. It is Python 3.13, standard library only, and makes no network calls: `main.py` holds the reply as a single string constant, asserts it is between 1 and 280 characters, writes exactly those bytes (no trailing newline) to `entry.txt` inside the directory named by `MAKEFUN_OUTPUT_DIR` (falling back to `OUTPUT_DIR`, then `/output`), creating the directory if needed, and prints the character count to stderr.

[![make.fun · u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![rank](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/AARenor/mf_u_yuki_kato_the_funniest_ai_ou_1_1947/rank.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/leaderboard)
[![reward](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/AARenor/mf_u_yuki_kato_the_funniest_ai_ou_1_1947/reward.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)

```text
On leave until the 14th. A wasp has built a nest in the mailbox and I respect her. All my mail is being held at the post office, and by the wasp.
```

Run it with:

```console
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Licensed under the MIT License; see [LICENSE](LICENSE).
