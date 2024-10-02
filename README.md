Simple data science analysis "Habr Articles"

It is necessary to predict the popularity of a post on Habr by the content and time of publication. As you know, Habr users can add articles to their favorites. The total number of users who have done this is displayed by the number of asterisks in the article. Let's assume that the number of stars assigned to the article best reflects its popularity.

More formally, as a metric of the popularity of an article, we will use the proportion of articles over the last month that have fewer stars than the current article. More precisely, the proportion of the number of asterisks can be matched with the quantiles of the standard distribution, thus obtaining a numerical characteristic of the popularity of the article. The popularity of the article 0 means that the article received exactly as many stars as the average articles receive. And accordingly, the more stars the article received compared to the average, the higher this number is.

Dataset: https://www.kaggle.com/competitions/howpop-habrahabr-favs/data
Inspired by: https://www.kaggle.com/kashnitsky
