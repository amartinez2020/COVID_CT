
# Classification of COVID-19 in CT Scans using Multi-Source Transfer Learning
https://arxiv.org/abs/2009.10474

### Alejandro R. Martinez
### Dartmouth College
### alejandro.r.martinez.20@dartmouth.edu

## Abstract
Since December of 2019, novel Coronavirus COVID-19   has   spread   around   the   world   infecting   millions of people  and  upending  the  global  economy.  One  of  the  main reasons  for  its  high  rate  of  infection  is  due  to  the  unreliability and  lack  of  RT-PCR  testing.  As  an  alternative,  recent  research has  investigated  the  use  of  Convolutional  Neural  Networks  for the  classification  of  COVID-19  from  CT  scans.  Because  there  is an  inherent  lack  of  available  COVID-19  CT  data,  researchers are  forced  to  leverage  the  use  of  Transfer  Learning.  Transfer Learning  has  shown  to  improve  model  performance  on  tasks that require  relatively  small  amounts  of  data,  as  long  as  the  Source feature   space   is   not   too   different   from   the   Target   featurespace.  This  difference  is  often  encountered  in  the classification   of   medical   images   as   publicly   available   Source datasets usually lack the visual features found in medical images. In  this  study,  we  propose  the  use  of  Multi-Source  Transfer Learning (MSTL) to improve upon traditional Transfer Learning for  the  classification  of  COVID-19  from  CT  scans.  With  our multi-source   fine-tuning   approach,   our   models   outperformed baseline   models   fine-tuned   with   ImageNet.   We   additionally propose an unsupervised label creation process, which enhances the   performance of   our   Deep   Residual   Networks.   Our best performing model was able to achieve an accuracy of 0.893 and a  Recall  score  of  0.897,  outperforming  its  baseline  Recall  score by  9.3%.




