---
title: "ST-Seq2Seq: A Spatio-Temporal Feature-Optimized Seq2Seq Model for Short-Term Vessel Trajectory Prediction"
collection: publications
permalink: /publication/IEEE-ACCESS
date: 2020-12-02
venue: 'IEEE ACCESS'
citation: 'You, L., Xiao, S., Peng, Q., Claramunt, C., Han, X., Guan, Z., & Zhang, J. (2020). St-seq2seq: A spatio-temporal feature-optimized seq2seq model for short-term vessel trajectory prediction. IEEE Access, 8, 218565-218574.'
---
**Abstract:** Deep learning provides appropriate mechanisms to predict vessel trajectories for safer and efficient shipping, but still existing models are mainly oriented to longer-term prediction trends and do not fully support real time navigation needs. While most recent works have been largely exploiting Automatic Identification System (AIS), the complete semantics of these data haven't so far fully exploited. The research presented in this paper introduced an extended sequence-to-sequence model using AIS data. A Gated Recurrent Unit (GRU) network encodes historical spatio-temporal sequences as a context vector, which not only preserves the sequential relationships among trajectory locations, but also alleviates the gradient descent problem. The GRU network acts as a decoder, outputting target trajectory location sequences. Real AIS data from the Chongqing and Wuhan sections of the Yangzi River were selected as typical experimental areas for evaluation purposes. The proposed ST-Seq2Seq model has been tested against the LSTM-RNN and GRU-RNN baseline models for short term trajectory prediction experiments. A 10-minute historical trajectory sequence was used to predict the trajectory sequence for the next five minutes. Overall, the findings show that LSTM and GRU networks, while applying a recursive method to predict a sequence of continuous trajectory points, when the number of predicted trajectory points increases accuracy decreases. Conversely, the extended sequence-to-sequence model shows satisfactory stability on different ship channels.  
<br>
Download <a href="https://ieeexplore.ieee.org/abstract/document/9276488">here</a>
