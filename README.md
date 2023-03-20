# Sentence order prediction

This project trains the model with a list of 5 sentences and their corresponding order (e.g [sentence 1, sentence 2, sentence 3, sentence 4, sentence 5], [1,2,3,4,5]) and predicts the correct order of sentences from new dataset. The model is from https://github.com/fabrahman/ReBART. See the citation below.

Result:
0.87 accuracy score

<img width="1280" alt="Screenshot 2023-03-20 at 11 37 43 AM" src="https://user-images.githubusercontent.com/40011512/226240960-e9702121-5603-44ef-9363-a0b6a99d77cc.png">


Citation: 
@inproceedings{Basu-brahman-chaturvedi-rebart,
    title = "Is Everything in Order? A Simple Way to Order Sentences",
    author = "Somnath Basu Roy Chowdhury, Faeze Brahman and
      Snigdha Chaturvedi",
    booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing (EMNLP)",
    month = nov,
    year = "2021",
    publisher = "Association for Computational Linguistics",
}
