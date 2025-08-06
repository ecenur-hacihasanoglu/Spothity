# SpotHity 🎧 — Predicting Spotify Track Popularity with Audio **and** Lyrics
> **Course project — BİL 476/573 (Data Mining), TOBB ETÜ**  
> Author: **Ecenur Hacıhasanoğlu**

A 7 k-track, multi-modal data‐mining pipeline that blends **Spotify audio features** with  
**Genius lyrics sentiment & topic signals** to predict the Spotify *popularity* score (0–100).

| Model | Features | Test RMSE ↓ | Test R² ↑ |
|-------|----------|-------------|-----------|
| XGBoost | audio + lyrics/emotion/topic | **13.22** | **0.444** |
| XGBoost | audio-only | 15.35 | 0.250 |

> ➜ **12 % error reduction** by adding text features  

## 📂 Repository structure
create_data -> Contains the whole data gathering and creation pipeline
audio_and_lyrics_data -> Contains data preperation and model results for the data that contains audio and lyrics attributes
only_audio_data -> Contains data preperation and model results for the data that contains only audio attributes
