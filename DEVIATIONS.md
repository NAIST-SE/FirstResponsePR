We required certain unavoidable deviations from the registered report, which are summarized below:
* **Data Source Changes.** The single deviation is the data source. We used GHTorrent dataset from [1] instead of from [2] dataset since it provides a larger and updated dataset (as to 2021.) We describe this change in <Section 2, Page 4>.
* **Metrics and Analysis Changes.** We identify three deviations.
  * (1) We removed AUROC for all of the tool because AUROC needs the probability of the data point belong to each class, which is not provided by the tool. This is described in <Section 2.1, Page 7>. 
  * (2) We also cannot report the precision, recall, and F1 score for the sentiment tool.
	     This is because the manual validation is binary ( based on agree/not agree ), which the sentiment is a scale from 1 to 5. 
	     This is described in <Section 2.1, Page 7>. 
  * (3) For the analysis and visualization of the results, we use violinplots instead of a boxplot to visualized RQ1 <Section 3.1, Page 9> and RQ2 <Section 3.2, Page 13>
* **Methodology Changes.**  
	    We identify two deviations.
  * (1)  We change to method for alleviating duplicated identity threat. As [3] approach focuses on merging the identity on the commit level not the GitHub account level, we found that it is difficult to apply this approach. Instead, we manually check for the multiple identities systematically during the sanity check. This is described in <Section 2.1, Page 7>.
  * (2) Instead of the tedious card sorting by all authors, similar to [4] and [5], we used manual coding with four authors that reach an agreement with a Kappa-agreement.
	    Details are described in <Section 3.2, Page 11>.

References

[1] G. Gousios.  The ghtorrent dataset and tool suite.  InProceedings of the 10th Working Conferenceon  Mining  Software  Repositories,  MSR  ’13,  pages  233–236,  Piscataway,  NJ,  USA,  2013.  IEEEPress.  ISBN 978-1-4673-2936-1.

[2] H. Hata, C. Treude, R. G. Kula, and T. Ishio. 9.6 million links in source code comments:  Purpose,evolution,  and  decay.   InProceedings  of  the  International  Conference  on  Software  Engineering,page 1211–1221, 2019.

[3] T. Fry, T. Dey, A. Karnauch, and A. Mockus. A dataset and an approach for identity resolution of 38 million author ids extracted from 2b git commits. InProceedings of the International Conferenceon Mining Software Repository, page 518–522, 2020.

[4] D.  Wang,  T.  Xiao,  P.  Thongtanunam,  R.  G.  Kula,  and  K.  Matsumoto.   Understanding  sharedlinks and their intentions to meet information needs in modern code review:.Empirical SoftwareEngineering, 26(5):96, Jul 2021.  ISSN 1573-7616.  doi:  10.1007/s10664-021-09997-x.  URLhttps://doi.org/10.1007/s10664-021-09997-x.

[5]  Z. Li, Y. Yu, T. Wang, G. Yin, S. Li, and H. Wang.  Are you still working on this an empiricalstudy on pull request abandonment.IEEE Transactions on Software Engineering, pages 1–1, 2021.
