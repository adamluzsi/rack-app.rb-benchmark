
## [Benchmarking](https://github.com/rack-app/rack-app-benchmark)

This is a repo that used for measure Rack::App project speed in order keep an eye on the performance in every release.

the benchmarking was taken on the following hardware specification:
* Processor: 2,7 GHz Intel Core i5
* Memory: 16 GB 1867 MHz DDR3
* Ruby: ruby 2.1.2p95 (2014-05-08 revision 45877) [x86_64-darwin15.0]


### Endpoint to be call type: static


#### number of declared endpoints: 100

| name                   | version                | current / fastest      | real                   |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| rack                   | 1.6.4                  | 1.0                    | 1.6755999999997824e-06 |
| rack-app               | 0.23.0                 | 12.949                 | 2.169760000000045e-05  |
| ramaze                 | 2012.12.08             | 24.828                 | 4.1601999999999315e-05 |
| hobbit                 | 0.6.1                  | 40.391                 | 6.76790000000015e-05   |
| brooklyn               | 0.0.1                  | 72.983                 | 0.00012229050000000643 |
| nancy                  | 0.3.0                  | 91.488                 | 0.00015329779999998726 |
| scorched               | 0.25                   | 179.476                | 0.00030072970000003256 |
| sinatra                | 1.4.7                  | 191.033                | 0.00032009470000000435 |
| rails                  | 4.2.5.1                | 453.927                | 0.0007605999000000241  |
| camping                | 2.1.532                | 574.146                | 0.0009620388000000196  |
| grape                  | 0.14.0                 | 582.409                | 0.000975884299999979   |
| cuba                   | 3.5.0                  | 763.772                | 0.001279777100000003   |


#### number of declared endpoints: 200

| name                   | version                | current / fastest      | real                   |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| rack                   | 1.6.4                  | 1.0                    | 1.6755999999997824e-06 |
| rack-app               | 0.23.0                 | 14.267                 | 2.3905600000000668e-05 |
| ramaze                 | 2012.12.08             | 23.738                 | 3.9775499999991495e-05 |
| hobbit                 | 0.6.1                  | 73.919                 | 0.00012385869999999795 |
| brooklyn               | 0.0.1                  | 114.538                | 0.00019192030000001126 |
| nancy                  | 0.3.0                  | 119.342                | 0.0001999692999999952  |
| scorched               | 0.25                   | 207.3                  | 0.00034735129999995015 |
| sinatra                | 1.4.7                  | 249.078                | 0.0004173551000000015  |
| rails                  | 4.2.5.1                | 405.476                | 0.0006794153636363568  |
| camping                | 2.1.532                | 944.217                | 0.0015821295999997641  |
| grape                  | 0.14.0                 | 948.344                | 0.0015890453999999742  |
| cuba                   | 3.5.0                  | 1463.332               | 0.0024519583000002674  |


#### number of declared endpoints: 500

| name                   | version                | current / fastest      | real                   |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| rack                   | 1.6.4                  | 1.0                    | 1.6755999999997824e-06 |
| rack-app               | 0.23.0                 | 12.152                 | 2.036200000000024e-05  |
| ramaze                 | 2012.12.08             | 27.803                 | 4.6586999999996584e-05 |
| hobbit                 | 0.6.1                  | 171.85                 | 0.00028795210000004173 |
| nancy                  | 0.3.0                  | 217.764                | 0.0003648853999999696  |
| brooklyn               | 0.0.1                  | 252.873                | 0.00042371389999999634 |
| scorched               | 0.25                   | 342.112                | 0.0005732426000000242  |
| sinatra                | 1.4.7                  | 470.873                | 0.0007889939999999797  |
| rails                  | 4.2.5.1                | 526.388                | 0.0008820155333333408  |
| camping                | 2.1.532                | 2249.727               | 0.0037696422999999157  |
| grape                  | 0.14.0                 | 2946.348               | 0.0049369003999997435  |
| cuba                   | 3.5.0                  | 3931.736               | 0.006588016699999495   |


#### number of declared endpoints: 1000

| name                   | version                | current / fastest      | real                   |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| rack                   | 1.6.4                  | 1.0                    | 1.6755999999997824e-06 |
| rack-app               | 0.23.0                 | 14.045                 | 2.3533700000001645e-05 |
| ramaze                 | 2012.12.08             | 21.242                 | 3.559349999999346e-05  |
| nancy                  | 0.3.0                  | 371.001                | 0.0006216494999999444  |
| hobbit                 | 0.6.1                  | 406.661                | 0.000681401100000034   |
| rails                  | 4.2.5.1                | 464.154                | 0.0007777361333332345  |
| brooklyn               | 0.0.1                  | 475.571                | 0.0007968676000000058  |
| scorched               | 0.25                   | 567.279                | 0.0009505325999999906  |
| sinatra                | 1.4.7                  | 837.946                | 0.0014040620000000943  |
| camping                | 2.1.532                | 4657.269               | 0.007803720299999039   |
| cuba                   | 3.5.0                  | 7703.007               | 0.01290715909999841    |
| grape                  | 0.14.0                 | 8344.355               | 0.01398180099999957    |

### Endpoint to be call type: dynamic


#### number of declared endpoints: 100

| name                   | version                | current / fastest      | real                   |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| rack                   | 1.6.4                  | 1.0                    | 2.611365853659144e-06  |
| rack-app               | 0.23.0                 | 9.346                  | 2.4404700000000905e-05 |
| ramaze                 | 2012.12.08             | 18.246                 | 4.764709999999912e-05  |
| brooklyn               | 0.0.1                  | 48.828                 | 0.00012750830000000184 |
| nancy                  | 0.3.0                  | 53.341                 | 0.00013929230000001214 |
| hobbit                 | 0.6.1                  | 53.586                 | 0.00013993159999999558 |
| scorched               | 0.25                   | 128.4                  | 0.0003352987999999926  |
| sinatra                | 1.4.7                  | 149.34                 | 0.00038998010000003094 |
| grape                  | 0.14.0                 | 306.273                | 0.0007997899000000149  |
| rails                  | 4.2.5.1                | 378.476                | 0.0009883387000002746  |
| camping                | 2.1.532                | 435.877                | 0.0011382348000000303  |
| cuba                   | 3.5.0                  | 470.242                | 0.0012279743000001766  |


#### number of declared endpoints: 200

| name                   | version                | current / fastest      | real                   |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| rack                   | 1.6.4                  | 1.0                    | 2.611365853659144e-06  |
| rack-app               | 0.23.0                 | 10.536                 | 2.7513499999999685e-05 |
| ramaze                 | 2012.12.08             | 16.336                 | 4.266040000000076e-05  |
| brooklyn               | 0.0.1                  | 73.146                 | 0.00019101159999999098 |
| nancy                  | 0.3.0                  | 75.299                 | 0.0001966331000000129  |
| hobbit                 | 0.6.1                  | 79.27                  | 0.00020700260000000332 |
| scorched               | 0.25                   | 140.91                 | 0.0003679684999999696  |
| sinatra                | 1.4.7                  | 186.67                 | 0.0004874624000000554  |
| rails                  | 4.2.5.1                | 278.766                | 0.0007279602000000549  |
| grape                  | 0.14.0                 | 485.139                | 0.0012668758000000703  |
| camping                | 2.1.532                | 701.243                | 0.0018312010000000542  |
| cuba                   | 3.5.0                  | 960.718                | 0.0025087859000000982  |


#### number of declared endpoints: 500

| name                   | version                | current / fastest      | real                   |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| rack                   | 1.6.4                  | 1.0                    | 2.611365853659144e-06  |
| rack-app               | 0.23.0                 | 8.643                  | 2.2570599999999895e-05 |
| ramaze                 | 2012.12.08             | 15.512                 | 4.050760000000559e-05  |
| nancy                  | 0.3.0                  | 138.969                | 0.0003628982000000345  |
| hobbit                 | 0.6.1                  | 163.382                | 0.0004266508999999747  |
| brooklyn               | 0.0.1                  | 193.53                 | 0.0005053780999999691  |
| scorched               | 0.25                   | 218.179                | 0.0005697461000000373  |
| rails                  | 4.2.5.1                | 293.723                | 0.000767018500000151   |
| sinatra                | 1.4.7                  | 311.568                | 0.0008136172000000295  |
| grape                  | 0.14.0                 | 1620.644               | 0.004232093600000211   |
| camping                | 2.1.532                | 1647.598               | 0.0043024817000006255  |
| cuba                   | 3.5.0                  | 2780.501               | 0.007260905699999937   |


#### number of declared endpoints: 1000

| name                   | version                | current / fastest      | real                   |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| rack                   | 1.6.4                  | 1.0                    | 2.611365853659144e-06  |
| rack-app               | 0.23.0                 | 10.915                 | 2.850280000000108e-05  |
| ramaze                 | 2012.12.08             | 14.194                 | 3.70670000000009e-05   |
| nancy                  | 0.3.0                  | 245.336                | 0.000640662099999988   |
| rails                  | 4.2.5.1                | 285.463                | 0.0007454475999999935  |
| hobbit                 | 0.6.1                  | 300.686                | 0.0007852010000000625  |
| scorched               | 0.25                   | 372.383                | 0.0009724287999999485  |
| brooklyn               | 0.0.1                  | 372.977                | 0.0009739783999999884  |
| sinatra                | 1.4.7                  | 526.626                | 0.0013752134000000334  |
| camping                | 2.1.532                | 3089.376               | 0.008067490699999048   |
| grape                  | 0.14.0                 | 4239.916               | 0.011071972599998467   |
| cuba                   | 3.5.0                  | 5433.661               | 0.014189277100001115   |
