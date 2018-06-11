# Disease-normalization Results

Experimental progress over time.

| Date | Changes | Accuracy | Acc. reach. | Compare | Commit |
| ---- | ------- | -------- | ----------- | ------- | ------ |
2018-06-01 10:25:44 | automatic result recording | 0.6645 | 0.9074 | [diff](../../commit/45b43bd2f376a663c24a0229054ad81c65988071) | [original](https://github.com/en-dash/disease-normalization/commit/50c8e01a8dd8da51af19b6ec261aeb6f1320178b)
2018-06-04 07:51:20 | no oracle in training | 0.7027 | 0.9140 | [diff](../../commit/05d7532a652e545b15134c14d70c0b0bccecd693) | [original](https://github.com/en-dash/disease-normalization/commit/be41ed10685845ff06e85a86dc8e50066988e64d)
2018-06-04 08:18:19 | predict from 1000 candidates | 0.3037 | 0.3361 | [diff](../../commit/237b7cc4af73d8b2e5cbddf71855ab91d029c70d) | [original](https://github.com/en-dash/disease-normalization/commit/be41ed10685845ff06e85a86dc8e50066988e64d)
2018-06-04 08:31:27 | train and predict with 1000 candidates | 0.1309 | 0.1449 | [diff](../../commit/c23c1733facb0ac5864703ceeeb844fda9a94331) | [original](https://github.com/en-dash/disease-normalization/commit/be41ed10685845ff06e85a86dc8e50066988e64d)
2018-06-05 13:57:01 | represent mentions with subword units | 0.6645 | 0.8645 | [diff](../../commit/d2e161a171cb55eba60a95c7489d616ce7818be4) | [original](https://github.com/en-dash/disease-normalization/commit/eef49b47ffbe7c1733a21b9edb06998e4f98747f)
2018-06-07 14:45:37 | candidate generation: similarity of phrase vectors | 0.5044 | 0.7548 | [diff](../../commit/95fa48f4f83309553717ee3068dbb205760d851c) | [original](https://github.com/en-dash/disease-normalization/commit/ba8d6b5f2938a8936d4c5a8cf77315e5041261a5)
2018-06-07 14:52:36 | subword-unit embeddings for candidate generation and CNN | 0.3062 | 0.6770 | [diff](../../commit/e624ace6543f565eeaa46e848cafffeb50fe3cb6) | [original](https://github.com/en-dash/disease-normalization/commit/031146c9bf23ef3054133f70e1689299beab844d)
2018-06-07 15:05:48 | both skip-gram overlap and phrase-embedding for candidate gen. | 0.5972 | 0.7165 | [diff](../../commit/2a5897290d1bd1089b366f929e8435464d841b5d) | [original](https://github.com/en-dash/disease-normalization/commit/bcba7276f821a0e2792800b0e83dc7ce21d436b3)
2018-06-08 10:31:56 | candidate generators provide a score for each candidate | 0.6874 | 0.8272 | [diff](../../commit/826aedbe433e0afbbb8ed8faf72c96bf8b36a592) | [original](https://github.com/en-dash/disease-normalization/commit/72a9a2c55c7a13c5d9c06e09ea95af8881e8fa2e)
2018-06-08 10:38:22 | switch back to using only skip-gram candidates | 0.6811 | 0.886 | [diff](../../commit/09e463d456740abe78d56f5c42a74257b403cb7b) | [original](https://github.com/en-dash/disease-normalization/commit/72a9a2c55c7a13c5d9c06e09ea95af8881e8fa2e)
2018-06-11 11:01:30 | new candidate generator based on actual cosine similarity | 0.7433 | 0.8616 | [diff](../../commit/b8a6c8c7637026075b589bb73930bb5f7d7e5478) | [original](https://github.com/en-dash/disease-normalization/commit/e001e6f27d0a20426f4fbfdd44c3468ebf947b62)
2018-06-11 11:20:25 | use candidates from cosine similarity only | 0.77 | 0.8951 | [diff](../../commit/97164f5e15d3c036f097d15a44cca95c7a9b24c2) | [original](https://github.com/en-dash/disease-normalization/commit/e001e6f27d0a20426f4fbfdd44c3468ebf947b62)
