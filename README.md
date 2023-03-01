# Poetry AI

My aim was to create an ML model that could be trained on the poems of any specific author and generate poetry that sounds like their work. I planned to train the model on two of my favorite authors, Mary Oliver and Edgar Allen Poe, as their styles are very different and I was interested in seeing if the model was versatile enough to analyze both poets' writing.

## Libraries
The following libraries are used in this project:
- numpy
- pandas
- random
- time
- datetime
- matplotlib.pyplot
- torch
- transformers

## Text Generation
To generate text, GPT-2 model is used. The process is as follows:

1. Text is preprocessed and tokenized using GPT-2 tokenizer.
2. Dataset is created using PoePoemDataset class.
3. Train/Validation split is performed.
4. Model is trained using create_model function.
5. New lines of poetry are generated using the trained model.

## Data and Code
The dataset used in this project is maryoliver_lines.csv, which contains poetry by Mary Oliver. Read more about the work on my website: www.benjaminchang.me/projects/poetry. Model based on GPT-2 (OpenAI) and code based on Scott Duda's previous work.

## Sample Generated Poems

When the sun stretches forward,
turning toward the sky,
I know what it is to feel
in the pulsing indigos of darkness.
I don’t doubt what a person wants to be—
to not only flutter but to have a pulse
where the great energies of the world
change us both into something better.
