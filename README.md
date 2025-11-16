# FDS Pokemon Challenge — Notes

- 🥇 final-2-0.ipynb  
  Achieved the best public leaderboard result in this workspace using a simple Logistic Regression model trained on a small set of hand-crafted features (team stat differences, lead matchup metrics, type-advantage counts, and a few timeline-derived signals).

- 🥈 final-3-0.ipynb  
  Uses a more engineered feature set and a stacking ensemble. Public leaderboard performance is similar to final-2-0, but the stacking solution shows signs of slight overfitting — roughly +0.5% higher accuracy on the training set compared to cross-validation.

---

### 📌 Kaggle context

This project targets the FDS Pokemon Battles Prediction challenge: predict whether the player wins a simulated Pokemon battle from pre-battle data and battle timelines. The dataset contains team details, lead information, and turn-by-turn timeline events; success depends on extracting compact, predictive features while avoiding overfitting.

```
                                  ,'\
    _.----.        ____         ,'  _\   ___    ___     ____
_,-'       `.     |    |  /`.   \,-'    |   \  /   |   |    \  |`.
\      __    \    '-.  | /   `.  ___    |    \/    |   '-.   \ |  |
 \.    \ \   |  __  |  |/    ,','_  `.  |          | __  |    \|  |
   \    \/   /,' _`.|      ,' / / / /   |          ,' _`.|     |  |
    \     ,-'/  /   \    ,'   | \/ / ,`.|         /  /   \  |     |
     \    \ |   \_/  |   `-.  \    `'  /|  |    ||   \_/  | |\    |
      \    \ \      /       `-.`.___,-' |  |\  /| \      /  | |   |
       \    \ `.__,'|  |`-._    `|      |__| \/ |  `.__,'|  | |   |
        \_.-'       |__|    `-._ |              '-.|     '-.| |   |
                                `'                            '-._|
```
