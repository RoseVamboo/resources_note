# 视频内容理解方面的paper,code,dataset

* Video Understanding
  * Video Classification
  * Action Recognition
  - Video Captioning
  - Temporal Action Detection

## Video Classification
 Title | Paper | Website | Category | Examples |Classes | Duration | Organizer | Dataset
--------------|-------|---------|----------|-----------|---------|----------|-----------|-----------------
UCF101: A Dataset of 101 Human Actions Classes From Videos in The Wild | [PDF][p1] | [Link][l1] | human action | 13,320 | 101 | <10s | UCF | UCF101
HMDB: A Large Video Database for Human Motion Recognition | [PDF][p2] | [Link][l2] | human action | 6,766 | 51 | <10s | Brown | HMDB51
ActivityNet: A Large-Scale Video Benchmark for Human Activity Understanding | [PDF][p8] | [Link][l8] | human activities | ~20,000 | 200 | - | ActivityNet | ActivityNet v1.3
Hollywood in Homes: Crowdsourcing Data Collection for Activity Understanding | [PDF][p4] | [Link][l4] | daily human activities | 9,848 | 157 | - | AI2 | Charades
The Kinetics Human Action Video Dataset | [PDF][p3] | [Link][l3] | human action | ~500,000 | 600 |  10s  | DeepMind  | Kinetics
Large-scale Video Classification with Convolutional Neural Networks | [PDF][p5] | [Link][l5] | sports | ~1 million | 478 | 5m36s | Google & Stanford | Sports-1M
YouTube-8M: A Large-Scale Video Classification Benchmark | [PDF][p6] | [Link][l6] | visual contents | ~7 million | 4716 | 120-500s | Google Cloud | YouTube-8M
Exploiting Feature and Class Relationships in Video Categorization with Regularized Deep Neural Networks | [PDF][p9] | [Link][l9] | visual contents |  91,223 | 239 | 100s+ | Fudan-Columbia | FCVID
The "something something" video database for learning and evaluating visual common sense | [PDF][p10] | [Link][l10] | action with objects |  108,499 | 174 | ~4s | TwentyBN | Something-Something
Moments in Time Dataset: one million videos for event understanding | [PDF][p7] | [Link][l7] | action or activity | ~1 million | 339 | 3s | MIT-IBM Watson | Moments in Time
HACS: Human Action Clips and Segments Dataset for Recognition and Temporal Localization | [PDF][p11] | [Link][l11] | recognition and localization | 520K | 200 | ~30.6s | MIT and Facebook | SLAC
## Action Recognition
Title | Paper | Website | Examples | Category | Organizer | Dataset
--------|-------|---------|-----------|-----------|-----------------
ActivityNet: A Large-Scale Video Benchmark for Human Activity Understanding| [PDF][p8] | [Link][l8] | ~20,000 | Temporal Action Detection | ActivityNet| ActivityNet v1.3
Broad Video Highlights | - | [Link][d2] | 18000 |Temporal Action Detection | Baidu | Broad Video Highlights
AVA: A Video Dataset of Spatio-temporally Localized Atomic Visual Actions | [PDF][s1] | [Link][m1] | 57.6k | Spatio-temporally Localized Atomic Visual Actions | Google & Berkeley| AVA

## Video Captioning 
Title | Paper | Website | Context | Examples | Organizer | Dataset
--------|-------|---------|----------|-----------|-----------|-----------------
MSR-VTT: A Large Video Description Dataset for Bridging Video and Language |[PDF][v1]| [Link][c1] | 20 categories| 10,000 clips wth 200,000 sentences| MSR | MSR-VTT
A Dataset for Movie Description |[PDF][v2]| [Link][c2] | movie | 68,337 clips with 68,375 sentences| MPII | MPII-MD
Dense-Captioning Events in Videos |[PDF][v3]| [Link][c3] | event | 20k clips and 100k sentences | Stanford, ActivityNet | Densevid
Hollywood in Homes: Crowdsourcing Data Collection for Activity Understanding |[PDF][p4]| [Link][l4] | human activity| 9,848 clips wth 27,847 sentences| AI2 | Charades

## Video Question Answering 
Dataset | Paper | Website | Task | Examples | Organizer | Dataset
--------|-------|---------|----------|-----------|-----------|-----------------
MovieQA: Understanding Stories in Movies Through Question-Answering. |[PDF][q1]| [Link][a1] | question-answering in movies | 408 movies & 14944 QAs| UToronto | MovieQA
MarioQA: Answering Questions by Watching Gameplay Videos |[PDF][q2]| [Link][a2] | reasoning events in game videos | 187,757 examples with 92,874 QAs| POSTECH | MarioQA


[p1]: http://crcv.ucf.edu/papers/UCF101_CRCV-TR-12-01.pdf
[l1]: http://crcv.ucf.edu/data/UCF101.php
[P2]: http://cbcl.mit.edu/publications/ps/Kuehne_etal_iccv11.pdf
[L2]: http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/
[p3]: https://arxiv.org/abs/1705.06950
[l3]: https://deepmind.com/research/open-source/open-source-datasets/kinetics/
[p4]: https://link.springer.com/chapter/10.1007/978-3-319-46448-0_31
[l4]: http://allenai.org/plato/charades/
[p5]: http://cs.stanford.edu/people/karpathy/deepvideo/deepvideo_cvpr2014.pdf
[l5]: http://cs.stanford.edu/people/karpathy/deepvideo/
[p6]: https://arxiv.org/abs/1609.08675
[l6]: https://research.google.com/youtube8m/
[p7]: http://moments.csail.mit.edu/data/moments_paper.pdf
[l7]: http://moments.csail.mit.edu/
[p8]: https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Heilbron_ActivityNet_A_Large-Scale_2015_CVPR_paper.pdf
[l8]: http://activity-net.org/index.html
[p9]: https://arxiv.org/abs/1502.07209
[l9]: http://bigvid.fudan.edu.cn/FCVID/
[p10]: https://arxiv.org/abs/1706.04261
[l10]: https://www.twentybn.com/datasets/something-something
[p11]: https://arxiv.org/abs/1712.09374
[l11]: http://slac.csail.mit.edu/ 

[t1]: http://crcv.ucf.edu/papers/UCF101_CRCV-TR-12-01.pdf
[d1]: http://crcv.ucf.edu/THUMOS14/download.html
[d2]: http://ai.baidu.com/broad/introduction?dataset=video

[h1]: https://www.twentybn.com/datasets/jester

[s1]: https://arxiv.org/abs/1705.08421
[m1]: https://research.google.com/ava/index.html

[v1]: https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf
[c1]: http://ms-multimedia-challenge.com/2017/
[v2]: https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Rohrbach_A_Dataset_for_2015_CVPR_paper.pdf
[c2]: https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/research/vision-and-language/mpii-movie-description-dataset/
[v3]: https://arxiv.org/abs/1705.00754
[c3]: https://cs.stanford.edu/people/ranjaykrishna/densevid/

[q1]: http://openaccess.thecvf.com/content_cvpr_2016/papers/Tapaswi_MovieQA_Understanding_Stories_CVPR_2016_paper.pdf
[a1]: http://movieqa.cs.toronto.edu/home/
[q2]: https://arxiv.org/abs/1612.01669
[a2]: http://cvlab.postech.ac.kr/research/MarioQA/

