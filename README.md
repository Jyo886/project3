
Name : Jyostna Marella


1. Basic Autoencoder (Q1)
What it does: Learns to compress and reconstruct images (like a "save as ZIP" for pictures)

Simple breakdown:
Takes MNIST handwritten digits (28x28 pixels)
Squeezes them down to 32 numbers (encoder)
Then tries to rebuild the original image from those 32 numbers (decoder)
Shows before/after pictures to see how good the reconstruction is
Key idea: It learns the most important parts of the image to keep during compression

2. Denoising Autoencoder (Q2)
What it does: Cleans up noisy images (like a "photo repair" tool)

Simple breakdown:
Takes clean images and adds random noise (like TV static)
Teaches the network to remove the noise and restore the original
Shows: noisy input → cleaned output → original for comparison
Works better than the basic autoencoder for noisy images
Key idea: Learns what real images should look like, ignores random noise

3. Text Generation RNN (Q3)
What it does: Writes Shakespeare-like text one letter at a time

Simple breakdown:
Reads Shakespeare's sonnets character by character
Learns patterns like "q is usually followed by u"
Can continue writing given a starting phrase
"Temperature" controls creativity vs predictability:
Low = safe, repetitive (always picks most likely next letter)
High = wild, sometimes nonsense (takes more risks)
Key idea: Predicts the next most likely character based on what it's seen before

4. Sentiment Analysis RNN (Q4)
What it does: Decides if movie reviews are thumbs up (👍) or thumbs down (👎)

Simple breakdown:
Reads 50,000 IMDB movie reviews
Learns which words predict positive/negative reviews
(e.g., "awesome" → positive, "terrible" → negative)
Shows:
Accuracy: How often it's right overall
Confusion matrix: Right/wrong counts
Precision/Recall tradeoff:
High precision: When it says "positive", it's probably right
High recall: Catches most actual positive reviews
Key idea: Understands the emotional tone of text by learning word patterns
Each example shows neural networks learning different skills - from working with images to understanding and generating text!
