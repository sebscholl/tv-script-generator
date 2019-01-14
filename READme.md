# TV Script Generator

### Project

Using Seinfeld's 9th season as training data, I modeled a Recurrent Neural Network (RNN) that will generate TV show scripts "like" Seinfeld. 

### Example

#### Input

input = "Jerry"

#### Output

- jerry: what about me?
- jerry: i don't have to wait.
- kramer:(to the sales table)
- elaine:(to jerry) hey, look at this, i'm a good doctor.
- newman:(to elaine) you think i have no idea of this...
- elaine: oh, you better take the phone, and he was a little nervous.
- kramer:(to the phone) hey, hey, jerry, i don't want to be a little bit.(to kramer and jerry) you can't.
- jerry: oh, yeah. i don't even know, i know.
- jerry:(to the phone) oh, i know.
- kramer:(laughing) you know...(to jerry) you don't know.

### Notes

As you can see, coherency is not the models forte... However, the model was only trained for 10 Epochs and achieved a training loss of ~3.3. 