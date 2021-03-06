In this work, we study the problem of text removal using inpainting techniques with Generative Adversarial Networks.
It is a very challenging problem due to the fact that can be divided into 2 separate, that of text localization and that of inpainting the localized texts. 

We try several approaches to the problem, starting with the well-studied supervised training to study their results and improvements. 
We then try to take advantage of great inpainting success of conditional adversarial techniques using a cGAN. 
Finally, we use additive text localization networks to contribute to more realistically inpainting by facilitating the text localization task. 

Despite the fact that the additive networks significantly improved the inpainting results, we investigate whether the network’s depth shrinkage by integrating attention gates (AG) will offer the same impressive results. Although, elimination of explicit external localisation modules does not offer more realistic inpainting, still contribute to localization task and the results are worth studying.