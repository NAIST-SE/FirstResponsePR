We summarized the deviations of our paper from the registered report plan as follows:
  * **Data Source Changes.** We used GHTorrent dataset[1] instead of [2] dataset since it provide more updated data (as to 2021.)
  * **Metrics and Analysis Changes.** We modified the evaluation metrics in the sanity check. We decided to remove AUROC for all of the tool because AUROC need the probability of the data point belong to each class; and the tools we are using do not provide it. Additionally, we cannot report precision, recall, and F1 score for the sentiment tool as our manual validation is based on agree/not agree with the result of the tool; therefore we could not apply the calculation of these metrics to the output of sentiment tool. Additionally, we decided to use violinplot instead of boxplot to visualized RQ1 and RQ2 results since it provide more insight into how the data distributed.
  * **Methodology changes.** We change to method for alleviating duplicated identity thread. As [3] approach focuses on merging the identity on the commit level not the GitHub account level, we found that it is difficult to apply this approach to this study. We ensure that our data does not strongly effect by the multiple identity by checking for the multiple identity along the way we perform the manual investigations in this research (i.e. sanity check) Furthermore, we used method as in [4] instead of card sorting as in [5] for creating the taxonomy of the negative first response in RQ2. This is because this approach is faster and easier to perform.

References

[1] G. Gousios.  The ghtorrent dataset and tool suite.  InProceedings of the 10th Working Conferenceon  Mining  Software  Repositories,  MSR  ’13,  pages  233–236,  Piscataway,  NJ,  USA,  2013.  IEEEPress.  ISBN 978-1-4673-2936-1.

[2] H. Hata, C. Treude, R. G. Kula, and T. Ishio. 9.6 million links in source code comments:  Purpose,evolution,  and  decay.   InProceedings  of  the  International  Conference  on  Software  Engineering,page 1211–1221, 2019.

[3] T. Fry, T. Dey, A. Karnauch, and A. Mockus. A dataset and an approach for identity resolution of 38 million author ids extracted from 2b git commits. InProceedings of the International Conferenceon Mining Software Repository, page 518–522, 2020.

[4] D.  Wang,  T.  Xiao,  P.  Thongtanunam,  R.  G.  Kula,  and  K.  Matsumoto.   Understanding  sharedlinks and their intentions to meet information needs in modern code review:.Empirical SoftwareEngineering, 26(5):96, Jul 2021.  ISSN 1573-7616.  doi:  10.1007/s10664-021-09997-x.  URLhttps://doi.org/10.1007/s10664-021-09997-x.

[5]  Z. Li, Y. Yu, T. Wang, G. Yin, S. Li, and H. Wang.  Are you still working on this an empiricalstudy on pull request abandonment.IEEE Transactions on Software Engineering, pages 1–1, 2021.
