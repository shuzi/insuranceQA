This dataset is provided as is and for research purpose only.

answers.label.token_idx:

<answer label><TAB><answer text in word index form>  
To get the word of from its index idx_* ,  please use the file vocabulary

question.train.token_idx.label:

<question text in word index form><TAB><answer labels>
To get the word of from its index idx_* ,  please use the file vocabulary

question.(dev|test1|test2).label.token_idx.pool:

<ground truth labels><TAB><question text in word index form><TAB><answer candidate pool>
To get the word of from its index idx_* ,  please use the file vocabulary
Notice we make an answer candidate pool with size 500 here for dev, test1 and test2.
If running time is not a problem for your applicaiton, you are surely encouraged to use the whole answer set as the pool (label 1-24981).

vocabulary

<word index><TAB><original word>


