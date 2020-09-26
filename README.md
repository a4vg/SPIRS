# Reactive Supervision and SPIRS

Reactive upervision is a new method for capturing labeled data from social media. SPIRS is a sarcasm dataset collected using reactive supervision.
The reactive supervision paper will be available soon. 

 Use this repository to download SPIRS. The repository includes the following data files:

  * `SPIRS-sarcastic-ids.csv`
  * `SPIRS-non-sarcastic-ids.csv`

To comply with Twitter's privacy policy, the dataset files include only the tweet IDs.

To fetch the tweet texts, follow these steps:

  * Install the latest version of Tweepy:
  
    `pip3 install tweepy`
  * Rename `credentials-example.py` to `credentials.py`
  * Add your Twitter API credentials by editing `credentials.py`
  * Run the script:
  
    `python3 fetch-tweets.py`

The script will fetch the texts and create two new files, one for sarcastic and the other for non-sarcastic tweets.

## Citation

Kindly cite the paper using the following BibTex entry:

```
@inproceedings{
    shmueli:reactive-supervision, 
    title={Reactive Supervision: A New Method for Collecting Sarcasm Data}, 
    author={Shmueli, Boaz and Ku, Lun-Wei and Ray, Soumya}, 
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing", 
    year = "2020", 
    publisher = "Association for Computational Linguistics"
}
```

