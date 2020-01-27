# climate-nlp-dev

We're trying to get an overview about the sentiments of newspaper reports about climate change.

In order to do this, we download and extract text from english and german articles about climate change and use nlp to do a sentiment analysis afterwards.

## Usage

Run polarity on all `json` files in `~/climate-nlp/articles`, outputs into `~/climate-nlp/final/`

```bash
python analyze.py
```

TODAY = 

## Examples

unavoidable success vs unavoidable failure
cataclysmic, warm 
make no mistake
apocalyptic
succeeded only
increasing climate change -> negative
ambition
like (2) the melting of ice (like makes sentence positive)

## Climate specific examples

sea-level rise
rising temperature
flooding
refugees
fire
more rain in places where it already rains a lot, or less rain in dry places, or no (-1) rain at all

## `data/negation.txt`

## `data/intensity.txt`

Support the existing polarity of a word
- dosen't change the sign of the polarity

step-change
curb
growing
rising
very
shift

twenty feet of sea-level rise (1) (the number acts like an intensity)
