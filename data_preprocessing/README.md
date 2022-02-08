## Data preprocessing

This directory manages data directory. 

split total of data into train and test 

and then remove duplication of sentence. 

mkdir train and test corpus to ../corpus directory 


If you want to make head-tail corpus with pos tag

run this code line:

```
## With pos tagging
extract_function_call(pos_tag=True)
```

If you want not to make head-tail corpus with pos tag

run this code line:

```
## without pos tagging
## extract_function_call(pos_tag=False)
```

If you want the original full dataset, access the following URL:

For dataset/oo_total_data/

  for 00_kcc_q28_only,[KCC_Q28_Head_Tail_debugging_corpus](https://drive.google.com/file/d/1fmEuKuAI1ctGjdWjqEzOoUVBNnvxXDqL/view?usp=sharing)

  for 01_kcc_150_only,[KCC_150_Head_Tail_debugging_corpus](https://drive.google.com/file/d/1RMGay8-EPhIpIgLrLZmrulFTgtlXNDZN/view?usp=sharing)


For dataset/o1_train/
  
  for 00_kcc_q28_only_Train,[KCC_Q28_Head_Tail_debugging_Train_corpus](https://drive.google.com/file/d/1l2kslo69AOZIcwoM1Y9WL4kRjAHnOvaN/view?usp=sharing)

  for 01_kcc_150_only_Train,[KCC_150_Head_Tail_debugging_Train_corpus](https://drive.google.com/file/d/1uNA-f6OL2NQPvOpVu2pHPQ1lTrxfSe7d/view?usp=sharing)
  
  for 02_kcc_q28_n_150_only_Train,[KCC_Q28_AND_KCC150_Head_Tail_debugging_Train_corpus](https://drive.google.com/file/d/1rryHxwi-_T-NRtl3Q-cM3SJkD2JiAPvb/view?usp=sharing)


For dataset/o2_test/
  
  for 00_kcc_q28_only_Test,[KCC_Q28_Head_Tail_debugging_Test_corpus](https://drive.google.com/file/d/11z2DEKwe0kLlCVmP3NWguUcZ6dTqZOVe/view?usp=sharing)

  for 01_kcc_150_only_Test,[KCC_150_Head_Tail_debugging_Test_corpus](https://drive.google.com/file/d/1p97ywUJfDs6yYDzI811thhoHlMWShpDa/view?usp=sharing)
  
  for 02_kcc_q28_n_150_only_Test,[KCC_Q28_AND_KCC150_Head_Tail_debugging_Test_corpus](https://drive.google.com/file/d/1O-bUFrTws6ywVaWyrgPLv52qd9Cu2s2w/view?usp=sharing)
