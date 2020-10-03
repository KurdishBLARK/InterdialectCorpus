# Kurdish Parallel Corpus
## A parallel corpus of Kurdish (Sorani and Kurmanji) and English

This repository contains a parallel corpus of Sorani (`ckb`) and Kurmanji (`kmr`) dialects of Kurdish along with English (`eng`). The development of the corpus is described in [our paper](). Our approach is consisted of retrieving potentially-alignable news articles from multi-language websites and manually align them across dialects and languages based on lexical similarity and transliteration of scripts. 

Our parallel corpus contains three manually-aligned corpus in Sorani-Kurmanji, Sorani-English and Kurmanji-English in various formats, namely [Translation Memory eXchange](https://en.wikipedia.org/wiki/Translation_Memory_eXchange) file format (`.tmx`), parallel annotated text useful for [ParaConc](https://paraconc.com/) and raw parallel texts (`.txt`). In the latter, each line corresponds to the same line in the other aligned file.

This corpus contains **12,327** translation pairs in the two major dialects of Kurdish, Sorani and Kurmanji. We also provide **1,797** and **650** translation pairs in English-Kurmanji and English-Sorani. 

## Download

You can download the corpus as follows:

- Sorani-English [CKB-ENG](https://github.com/KurdishBLARK/InterdialectCorpus/tree/master/CKB-ENG) 
- Kurmanji-English [KMR-ENG](https://github.com/KurdishBLARK/InterdialectCorpus/tree/master/KMR-ENG)
- Sorani-Kurmanji  [CKB-KMR](https://github.com/KurdishBLARK/InterdialectCorpus/tree/master/CKB-KMR)


In addition, the statistical models reported as the baseline in our paper are provided in [Moses-results](https://github.com/KurdishBLARK/InterdialectCorpus/tree/master/Moses-results).

## How to cite this paper?

If you use any part of the data, please consider citing [our paper]() as follows:

	@inproceedings{,
	title={{Leveraging Multilingual News Websites for Building a Kurdish Parallel Corpus}},
	author={Ahmadi, Sina and Hassani, Hossein and Q. Jaff, Daban},
	pages={},
	year={2020}
	}


## License

This corpus is available under the [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://github.com/KurdishBLARK/InterdialectCorpus/blob/master/LICENSE) license. For further information for commercial use, please get in touch with the [contributors](https://github.com/KurdishBLARK/InterdialectCorpus/graphs/contributors).
