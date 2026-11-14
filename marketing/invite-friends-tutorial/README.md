# Sokas · Invite Friends tutorial (YouTube)

- `Sokas_Invite_Friends_Tutorial.mp4`: 1920×1080, 30 fps, 2:43, H.264 + AAC. Narration is the owner's voice file; Bengali subtitles are burned in.
- `Sokas_Invite_Friends_Thumbnail.png`: 1280×720 YouTube thumbnail.

The screens are the app's real Invite page (`assets/invite/index.html`), filled with demo data (names Rahim, Nusrat and Sakib; ID 12345678). The voice-room scene is not a screenshot: it is drawn from the app's own room layout (`activity_watch_audio_live.xml`, `item_seat.xml`), its icons and background, and the Invite Friends event image kept in the repository. It shows no real user.

Rewards shown come from `admin/backend/server/referral/referralRules.js`:
- 5,000 diamonds per friend for the inviter, plus 5% of the friend's recharges and 5% of their gifts for 30 days.
- 10,000 diamonds for the friend, plus the New badge, the New frame and a room theme for 30 days.
- A friend can still join by entering the inviter's ID within 7 days of opening a new account.
- The reward is given once per phone.
