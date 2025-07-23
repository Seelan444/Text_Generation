#  Shakespeare Text Generator 

This project trains a character-level LSTM model using TensorFlow to generate new text in the style of William Shakespeare.

##  What It Does

- Learns the structure of Shakespearean text
- Generates brand new dialogue based on a seed string
- Mimics poetic form, grammar, and character names
- Lets you control creativity with a "temperature" parameter

##  Technologies Used

- Python
- TensorFlow / Keras
- TensorFlow Datasets (`tiny_shakespeare`)
- LSTM (Long Short-Term Memory)
- Matplotlib (for loss plots)

##  How It Works

1. Loads the Tiny Shakespeare dataset (~100k characters)
2. Converts characters to integers (char2idx)
3. Creates input/target sequences (seq_length = 100)
4. Trains a 3-layer RNN:
   - Embedding
   - LSTM (stateful)
   - Dense (vocab logits)
5. Generates character-by-character predictions
6. Outputs original Shakespeare-style text

## 📈 Training Sample
<img width="688" height="548" alt="Screenshot 2025-07-23 164010" src="https://github.com/user-attachments/assets/39bcb2db-e2c2-4a5b-aab4-41b29e6dc63f" />


##  Output

📝 Generated Text:

QUEEN: So, lets end this braven to me; for I have heard
You should destroy his sovereign; and your brother is a comfort
Appling their fury: on the marketplace, that you now, then, bring them all.

BUSHY:
Why, that's the news with you.

Provost:
Alas, poor soul!

AUFIDIUS:
Where is thy conscience now?

SICINIUS:
This is a pals of them, and with him.

Servant:
What, think you
with him and therefore let him be a Margar't for her lip, and as
we thank the noble of my sorrow's royal kings
And harsh a double very true man's house,
Against the tide will be full of my sorrow!

KING LEWIS XI:
And let me die with continuing in the world,
I seem devotion as your father's head?

Provost:
Happily met! Has he among the town, one that is made for grace.

GLOUCESTER:
He that may chose but man? for we are soft from him,
Being a thought on Edward's easiest woman
Marcius combinets to all good words.

VOLUMNIA:
If I may live once more ing undo about the child:
And so deep as to be moved, you would be contributors
And bear the sho


