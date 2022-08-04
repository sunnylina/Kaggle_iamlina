# Natural_Language_Processing_with_Disaster_Tweets

## Organize names

- df_train = train.csv
- df_test = test.csv
- df_sample = sample_submission.csv
- df_train_cleaned = text_preprocessing(df_train, 'text')
- train_data = df_train_cleaned.copy()

##### Columns

- `id` – a unique identifier for each tweet
- `text` – the text of the tweet
- `location` – the location the tweet was sent from (may be blank)
- `keyword` – a particular keyword from the tweet (may be blank)
- `target` – in **train.csv** only, this denotes whether a tweet is about a real disaster (`1`) or not (`0`)
