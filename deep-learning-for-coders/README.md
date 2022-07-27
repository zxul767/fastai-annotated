# Motivation
One of the things I found disappointing in this course was the use of uninformative abbreviations which the make the code harder to read and remember.

To mitigate this to some extent, I've created this glossary with each original term as you'll find it in the book, a spelled-out term that is more informative (what I wish they would have used), and an brief explanation of it.

# Alphabetical Glossary

## B
`bs` (`batch_size`) -- Number of instances to load on any given iteration of the training loop.

## C
`cat_names` (`categorical_vars`) -- The names of the categorical variables in a tabular model.

`cont_names` (`continuous_vars`) -- The names of the continuous variables in a tabular model.

## F
`fns` (`filepaths`) -- Sometimes used to refer to a collection of (absolute) file paths.

## D
`dls` (`dataloaders`) -- An object that combines a data loader for training data and one for validation data.

`drop_mult` (`dropout_probability`) -- The probability in the "dropout" regularization to be applied in various layers of a model that takes this parameter.

## P
`procs` (`preprocessing_pipeline`) -- In the context of tabular models, this parameter specifies a list of functions (i.e., a pipeline) to be applied to the data before being passed to the model.

## I
`item_tfms` (`item_transforms`) -- All transformations applied to an image (in the context of a `DataLoader`) when loading from disk but before it is loaded on the GPU. These transformations are applied on the CPU.

## V
`valid_pct` (`validation_percentage`) -- The percentage of an input dataset to be used as a validation dataset.
