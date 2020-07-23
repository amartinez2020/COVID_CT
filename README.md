
 #Classification of COVID-19 in CT Scans using Multi-Source Transfer Learning

 ###Alejandro R. Martinez
 ###Dartmouth College
 ###alejandro.r.martinez.20@dartmouth.edu

 ##Abstract
Since December of 2019,novel Coronavirus COVID-19   has   spread   around   the   world   infecting   millionspeople  and  upending  the  global  economy.  One  of  the  mainreasons  for  its  high  rate  of  infection  is  due  to  the  unreliabilityand  lack  of  RT-PCR  testing.  As  an  alternative,  recent  researchhas  investigated  the  use  of  Convolutional  Neural  Networks  forthe  classification  of  COVID-19  from  CT  scans.  Because  there  isan  inherent  lack  of  available  COVID-19  CT  data,  researchersare  forced  to  leverage  the  use  of  Transfer  Learning.  TransferLearning  has  shown  to  improve  model  performance  on  taskswith  relatively  small  amounts  of  data,  as  long  as  the  Sourcefeature   space   is   not   too   different   from   the   Target   featurespace.  Unfortunately,  this  difference  is  often  encountered  in  theclassification   of   medical   images   as   publicly   available   Sourcedatasets usually lack the visual features found in medical images.In  this  study,  we  propose  the  use  of  Multi-Source  TransferLearning (MSTL) to improve upon traditional Transfer Learningfor  the  classification  of  COVID-19  from  CT  scans.  With  ourmulti-source   fine-tuning   approach,   our   models   outperformedbaseline   models   fine-tuned   with   ImageNet.   We   additionally,propose an unsupervised label creation process, which enhancesthe   performance   of   our   Deep   Residual   Networks.   Our   bestperforming model was able to achieve an accuracy of 0.893 anda  Recall  score  of  0.897,  outperforming  its  baseline  Recall  scoreby  9.3%.
