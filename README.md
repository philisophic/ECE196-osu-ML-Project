# ECE 196 osu!mania Machine Learning Project
Retrieves a player's top plays from the osu! v2 API, and uses them to train a Support Vector Regression machine learning model for predicting marvelous accuracy (MA) on a miscellaneous song.

Requires a config.json in the root directory containing an API key, as well as a maps\ folder containing the .osu beatmap files for the scores of interest.

Employs the [Maniera](https://github.com/NiceAesth/maniera), sklearn, and seaborn libraries.

Developed by Harrison Lew and Philip Lin.
