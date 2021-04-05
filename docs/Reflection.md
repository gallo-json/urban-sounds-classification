# Reflection

This was more of a learning experience. This was the final project of the ID tech camp, and the qualified instructors really helped me out on this one. I looked at other's solution to other problems and employed my own. As referenced in the "Useful links" section, I also used an article/vlog as guidance and inspiration. However, I did a lot of the troubleshooting on my own, and that gave me confidence after the camp to go an build my own models.

Keras was used because it was a high level machine learning library. At the time, TensorFlow was still at version 1 and was more lower-level. The two hadn't merged yet.

## Results

The model is clearly overfitting. I think this is due to the fact that the model is pretty simple (two Conv layers, two Dense layers), and CNNs may not be the best type of architecture for this kind of classification problems. Since audio is time series data, an RNN model would be more fitting. But in the 1 week camp we did not go over that. 

## What did I learn?

- Keras API
- Analyzing audio with Librosa
- Extracting data with Pandas