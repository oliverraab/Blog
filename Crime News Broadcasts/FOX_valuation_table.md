| Outcome      | Model                   | Best Cutoff | Best F1 | Precision | Recall |
|--------------|------------------------|------------|---------|-----------|--------|
| Democrat     | CNN Keras               | 0.0411     | 0.2366  | 0.1833    | 0.3333 |
| Democrat     | Logit + TF-IDF          | 0.0842     | 0.5806  | 0.6207    | 0.5455 |
| Democrat     | Logit + Emb             | 0.0901     | 0.4681  | 0.3607    | 0.6667 |
| Democrat     | Random Forest + TF-IDF  | 0.1000     | 0.4935  | 0.4318    | 0.5758 |
| Democrat     | Random Forest + Emb     | 0.1140     | 0.3238  | 0.2361    | 0.5152 |
| Democrat     | BERT                    | 0.0022     | 0.3611  | 0.3333    | 0.3939 |
| Riots        | CNN Keras               | 0.0332     | 0.1111  | 0.0645    | 0.4000 |
| Riots        | Logit + TF-IDF          | 0.0792     | 0.4167  | 0.5556    | 0.3333 |
| Riots        | Logit + Emb             | 0.1007     | 0.4444  | 0.5000    | 0.4000 |
| Riots        | Random Forest + TF-IDF  | 0.1060     | 0.6207  | 0.6429    | 0.6000 |
| Riots        | Random Forest + Emb     | 0.1620     | 0.3333  | 0.4444    | 0.2667 |
| Riots        | BERT                    | 0.0010     | 0.1176  | 0.5000    | 0.0667 |
| Cop_assault  | CNN Keras               | 0.1228     | 0.2105  | 0.2857    | 0.1667 |
| Cop_assault  | Logit + TF-IDF          | 0.0717     | 0.3902  | 0.2759    | 0.6667 |
| Cop_assault  | Logit + Emb             | 0.1248     | 0.3333  | 0.3333    | 0.3333 |
| Cop_assault  | Random Forest + TF-IDF  | 0.1360     | 0.3529  | 0.6000    | 0.2500 |
| Cop_assault  | Random Forest + Emb     | 0.1520     | 0.2143  | 0.1875    | 0.2500 |
| Cop_assault  | BERT                    | 0.0009     | 0.2188  | 0.1346    | 0.5833 |
| Abuse        | CNN Keras               | 0.0783     | 0.2041  | 0.1471    | 0.3333 |
| Abuse        | Logit + TF-IDF          | 0.0914     | 0.5000  | 0.4474    | 0.5667 |
| Abuse        | Logit + Emb             | 0.1340     | 0.5574  | 0.5484    | 0.5667 |
| Abuse        | Random Forest + TF-IDF  | 0.1820     | 0.3913  | 0.5625    | 0.3000 |
| Abuse        | Random Forest + Emb     | 0.1960     | 0.5238  | 0.9167    | 0.3667 |
| Abuse        | BERT                    | 0.0027     | 0.3860  | 0.4074    | 0.3667 |
| Mass         | CNN Keras               | 0.1314     | 0.4000  | 0.3846    | 0.4167 |
| Mass         | Logit + TF-IDF          | 0.0769     | 0.6207  | 0.5294    | 0.7500 |
| Mass         | Logit + Emb             | 0.1529     | 0.4762  | 0.5556    | 0.4167 |
| Mass         | Random Forest + TF-IDF  | 0.1440     | 0.7368  | 1.0000    | 0.5833 |
| Mass         | Random Forest + Emb     | 0.1540     | 0.2941  | 0.2273    | 0.4167 |
| Mass         | BERT                    | 0.0008     | 0.3478  | 0.3636    | 0.3333 |
| Dem_policies | CNN Keras               | 0.1718     | 0.4319  | 0.3333    | 0.6133 |
| Dem_policies | Logit + TF-IDF          | 0.1743     | 0.6790  | 0.6322    | 0.7333 |
| Dem_policies | Logit + Emb             | 0.1162     | 0.5377  | 0.4161    | 0.7600 |
| Dem_policies | Random Forest + TF-IDF  | 0.1740     | 0.6941  | 0.6211    | 0.7867 |
| Dem_policies | Random Forest + Emb     | 0.1920     | 0.5380  | 0.4792    | 0.6133 |
| Dem_policies | BERT                    | 0.0074     | 0.5584  | 0.4508    | 0.7333 |
| Immigration  | CNN Keras               | 0.0659     | 0.3546  | 0.2604    | 0.5556 |
| Immigration  | Logit + TF-IDF          | 0.1310     | 0.7229  | 0.7895    | 0.6667 |
| Immigration  | Logit + Emb             | 0.1461     | 0.6364  | 0.6512    | 0.6222 |
| Immigration  | Random Forest + TF-IDF  | 0.1560     | 0.8409  | 0.8605    | 0.8222 |
| Immigration  | Random Forest + Emb     | 0.2060     | 0.5600  | 0.7000    | 0.4667 |
| Immigration  | BERT                    | 0.0013     | 0.4286  | 0.3962    | 0.4667 |
| Biden        | CNN Keras               | 0.1220     | 0.2529  | 0.1667    | 0.5238 |
| Biden        | Logit + TF-IDF          | 0.1184     | 0.8085  | 0.7308    | 0.9048 |
| Biden        | Logit + Emb             | 0.1692     | 0.6000  | 0.6316    | 0.5714 |
| Biden        | Random Forest + TF-IDF  | 0.1760     | 0.8000  | 0.6897    | 0.9524 |
| Biden        | Random Forest + Emb     | 0.1960     | 0.5714  | 0.7143    | 0.4762 |
| Biden        | BERT                    | 0.0033     | 0.7222  | 0.8667    | 0.6190 |
| Trump        | CNN Keras               | 0.0458     | 0.2353  | 0.2000    | 0.2857 |
| Trump        | Logit + TF-IDF          | 0.0956     | 0.6024  | 0.4545    | 0.8929 |
| Trump        | Logit + Emb             | 0.1516     | 0.5079  | 0.4571    | 0.5714 |
| Trump        | Random Forest + TF-IDF  | 0.1400     | 0.4918  | 0.4545    | 0.5357 |
| Trump        | Random Forest + Emb     | 0.1180     | 0.3366  | 0.2329    | 0.6071 |
| Trump        | BERT                    | 0.0002     | 0.3265  | 0.3810    | 0.2857 |
| Crime        | CNN Keras               | 0.4850     | 0.8108  | 0.8203    | 0.8015 |
| Crime        | Logit + TF-IDF          | 0.4497     | 0.8169  | 0.7582    | 0.8855 |
| Crime        | Logit + Emb             | 0.4326     | 0.7939  | 0.7939    | 0.7939 |
| Crime        | Random Forest + TF-IDF  | 0.5420     | 0.8178  | 0.8707    | 0.7710 |
| Crime        | Random Forest + Emb     | 0.4640     | 0.7645  | 0.7734    | 0.7557 |
| Crime        | BERT                    | 0.9970     | 0.7344  | 0.7520    | 0.7176 |
