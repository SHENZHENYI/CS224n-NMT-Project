# NMT Assignment
Note: Heavily inspired by the https://github.com/pcyin/pytorch_nmt repository

trained on colab for less than half an hour -- early stopped at epoch 7, getting a BLEU score of 12.24.

epoch 6, iter 2610, avg. loss 53.62, avg. ppl 7.61 cum. examples 320, speed 1584.13 words/sec, time elapsed 731.90 sec
epoch 6, iter 2620, avg. loss 53.50, avg. ppl 8.35 cum. examples 640, speed 3461.67 words/sec, time elapsed 734.23 sec
epoch 6, iter 2630, avg. loss 51.72, avg. ppl 7.62 cum. examples 960, speed 3219.85 words/sec, time elapsed 736.76 sec
epoch 6, iter 2640, avg. loss 51.20, avg. ppl 7.69 cum. examples 1280, speed 3208.33 words/sec, time elapsed 739.27 sec
epoch 6, iter 2650, avg. loss 55.39, avg. ppl 7.85 cum. examples 1600, speed 3292.17 words/sec, time elapsed 741.88 sec
epoch 6, iter 2660, avg. loss 51.36, avg. ppl 7.47 cum. examples 1920, speed 3287.95 words/sec, time elapsed 744.37 sec
epoch 6, iter 2670, avg. loss 52.55, avg. ppl 7.33 cum. examples 2240, speed 3477.87 words/sec, time elapsed 746.79 sec
epoch 6, iter 2680, avg. loss 51.57, avg. ppl 7.66 cum. examples 2560, speed 3146.03 words/sec, time elapsed 749.37 sec
epoch 6, iter 2690, avg. loss 53.90, avg. ppl 8.21 cum. examples 2880, speed 3087.32 words/sec, time elapsed 752.02 sec
epoch 6, iter 2700, avg. loss 49.27, avg. ppl 7.25 cum. examples 3200, speed 3365.31 words/sec, time elapsed 754.39 sec
epoch 6, iter 2710, avg. loss 50.84, avg. ppl 7.13 cum. examples 3520, speed 3181.23 words/sec, time elapsed 756.99 sec
epoch 6, iter 2720, avg. loss 50.12, avg. ppl 7.74 cum. examples 3840, speed 3092.28 words/sec, time elapsed 759.53 sec
epoch 6, iter 2730, avg. loss 51.22, avg. ppl 7.34 cum. examples 4160, speed 3251.78 words/sec, time elapsed 762.06 sec
epoch 6, iter 2740, avg. loss 53.34, avg. ppl 7.92 cum. examples 4480, speed 3304.75 words/sec, time elapsed 764.55 sec
epoch 6, iter 2750, avg. loss 55.79, avg. ppl 8.17 cum. examples 4800, speed 2893.75 words/sec, time elapsed 767.49 sec
epoch 6, iter 2760, avg. loss 51.60, avg. ppl 7.62 cum. examples 5120, speed 3440.01 words/sec, time elapsed 769.85 sec
epoch 6, iter 2770, avg. loss 56.58, avg. ppl 8.15 cum. examples 5440, speed 3353.25 words/sec, time elapsed 772.43 sec
epoch 6, iter 2780, avg. loss 54.68, avg. ppl 7.67 cum. examples 5760, speed 2918.29 words/sec, time elapsed 775.37 sec
epoch 6, iter 2790, avg. loss 54.10, avg. ppl 7.56 cum. examples 6055, speed 3129.73 words/sec, time elapsed 777.89 sec
epoch 7, iter 2800, avg. loss 51.67, avg. ppl 7.26 cum. examples 6375, speed 3222.41 words/sec, time elapsed 780.48 sec
epoch 7, iter 2800, cum. loss 52.70, cum. ppl 7.67 cum. examples 6375
begin validation ...
validation: iter 2800, dev. ppl 39.616137
hit patience 1
hit #5 trial
early stop!


Decoding:   0% 0/1000 [00:00<?, ?it/s]/content/CS224n-NMT-Project/nmt_model.py:454: UserWarning: __floordiv__ is deprecated, and its behavior will change in a future version of pytorch. It currently rounds toward 0 (like the 'trunc' function NOT 'floor'). This results in incorrect rounding for negative values. To keep the current behavior, use torch.div(a, b, rounding_mode='trunc'), or for actual floor division, use torch.div(a, b, rounding_mode='floor').
  prev_hyp_ids = top_cand_hyp_pos // len(self.vocab.tgt)
Decoding: 100% 1000/1000 [00:42<00:00, 26.30it/s]
Corpus BLEU: 12.242131822188174