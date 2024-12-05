# Grocery Items Management Microservices Deployments

### © 2024 | Lyes Sefiane <img src="https://raw.githubusercontent.com/wiki/lyes-sefiane/grocery-items-management/images/algeria-flag-icon.png" width="2%"> <img src="https://raw.githubusercontent.com/wiki/lyes-sefiane/grocery-items-management-application/images/canada-flag-icon.png" width="2%"> All Rights Reserved | [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg

# GitHub Badges

![License](https://img.shields.io/static/v1?label=License&message=CC-BY-NC-ND-4.0&color=green)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

# Deployment to Localhost

```bash

Lyes Sefiane@******* ~/Documents/eclipse-workspace/deployments/grocery-items-management-microservices-deployment (main)
$ ./grocery-items-management-microservices


  ┏┓             ┳
  ┃┓┏┓┏┓┏┏┓┏┓┓┏  ┃╋┏┓┏┳┓┏
  ┗┛┛ ┗┛┗┗ ┛ ┗┫  ┻┗┗ ┛┗┗┛
  ┳┳┓         ┛          ┳┳┓•            •
  ┃┃┃┏┓┏┓┏┓┏┓┏┓┏┳┓┏┓┏┓╋  ┃┃┃┓┏┏┓┏┓┏┏┓┏┓┓┏┓┏┏┓
  ┛ ┗┗┻┛┗┗┻┗┫┗ ┛┗┗┗ ┛┗┗  ┛ ┗┗┗┛ ┗┛┛┗ ┛ ┗┛┗┗┗
            ┛


MINGW64_NT-10.0-19045 : Hi 😊 ! please make a selection.

1) Start Microservice
2) ShutDown Microservice
3) quit
#? 1
Start Grocery Items Management Microservice ...
 zipkin Pulling
 grocery-items-management-api-gateway Pulling
 consul-server Pulling
 grocery-items-management Pulling
 redis Pulling
 zipkin Pulled
 grocery-items-management Pulled
 da9db072f522 Already exists
 2b1287f8bbe9 Already exists
 90ed3939cee8 Pulling fs layer
 dc193cc5b74f Pulling fs layer
 944e9862aa5e Pulling fs layer
 443ba52fb7d8 Pulling fs layer
 443ba52fb7d8 Waiting
 5bafb31cae1b Already exists
 6da9b68c8106 Pulling fs layer
 e43f206c86b8 Pulling fs layer
 b0faedef9ffa Pulling fs layer
 a77c018aa078 Pulling fs layer
 613ded3f7b83 Pulling fs layer
 bd9ddc54bea9 Pulling fs layer
 a7297f4b08c3 Pulling fs layer
 6da9b68c8106 Waiting
 b0faedef9ffa Waiting
 e43f206c86b8 Waiting
 a77c018aa078 Waiting
 613ded3f7b83 Waiting
 bd9ddc54bea9 Waiting
 a7297f4b08c3 Waiting
 944e9862aa5e Downloading [>                                                  ]  47.83kB/4.749MB
 944e9862aa5e Downloading [=>                                                 ]  148.9kB/4.749MB
 90ed3939cee8 Downloading [==================================================>]     101B/101B
 90ed3939cee8 Verifying Checksum
 90ed3939cee8 Download complete
 90ed3939cee8 Extracting [==================================================>]     101B/101B
 944e9862aa5e Downloading [===>                                               ]  357.1kB/4.749MB
 90ed3939cee8 Extracting [==================================================>]     101B/101B
 944e9862aa5e Downloading [====>                                              ]  467.7kB/4.749MB
 944e9862aa5e Downloading [=======>                                           ]  668.4kB/4.749MB
 90ed3939cee8 Pull complete
 dc193cc5b74f Downloading [>                                                  ]  434.9kB/41.92MB
 dc193cc5b74f Downloading [=>                                                 ]  860.9kB/41.92MB
 944e9862aa5e Downloading [=======>                                           ]  729.8kB/4.749MB
 944e9862aa5e Downloading [========>                                          ]    779kB/4.749MB
 944e9862aa5e Downloading [==========>                                        ]  996.1kB/4.749MB
 944e9862aa5e Downloading [============>                                      ]  1.205MB/4.749MB
 944e9862aa5e Downloading [===============>                                   ]  1.471MB/4.749MB
 944e9862aa5e Downloading [==================>                                ]  1.717MB/4.749MB
 944e9862aa5e Downloading [===================>                               ]  1.815MB/4.749MB
 dc193cc5b74f Downloading [=>                                                 ]  1.287MB/41.92MB
 944e9862aa5e Downloading [====================>                              ]  1.914MB/4.749MB
 944e9862aa5e Downloading [=====================>                             ]   2.02MB/4.749MB
 dc193cc5b74f Downloading [==>                                                ]  1.713MB/41.92MB
 944e9862aa5e Downloading [======================>                            ]  2.184MB/4.749MB
 944e9862aa5e Downloading [=========================>                         ]  2.405MB/4.749MB
 dc193cc5b74f Downloading [==>                                                ]  2.139MB/41.92MB
 944e9862aa5e Downloading [===========================>                       ]  2.655MB/4.749MB
 944e9862aa5e Downloading [===============================>                   ]   2.95MB/4.749MB
 944e9862aa5e Downloading [=================================>                 ]  3.196MB/4.749MB
 dc193cc5b74f Downloading [===>                                               ]  2.561MB/41.92MB
 944e9862aa5e Downloading [==================================>                ]  3.294MB/4.749MB
 944e9862aa5e Downloading [====================================>              ]  3.441MB/4.749MB
 dc193cc5b74f Downloading [===>                                               ]  2.995MB/41.92MB
 944e9862aa5e Downloading [====================================>              ]  3.491MB/4.749MB
 944e9862aa5e Downloading [=====================================>             ]   3.54MB/4.749MB
 dc193cc5b74f Downloading [====>                                              ]  3.417MB/41.92MB
 944e9862aa5e Downloading [=====================================>             ]  3.589MB/4.749MB
 944e9862aa5e Downloading [========================================>          ]  3.892MB/4.749MB
 dc193cc5b74f Downloading [====>                                              ]  3.847MB/41.92MB
 944e9862aa5e Downloading [===========================================>       ]  4.093MB/4.749MB
 944e9862aa5e Downloading [===============================================>   ]  4.465MB/4.749MB
 dc193cc5b74f Downloading [=====>                                             ]  4.273MB/41.92MB
 944e9862aa5e Downloading [=================================================> ]  4.662MB/4.749MB
 944e9862aa5e Verifying Checksum
 944e9862aa5e Download complete
 dc193cc5b74f Downloading [=====>                                             ]  4.699MB/41.92MB
 dc193cc5b74f Downloading [======>                                            ]  5.133MB/41.92MB
 dc193cc5b74f Downloading [======>                                            ]  5.559MB/41.92MB
 dc193cc5b74f Downloading [=======>                                           ]  5.981MB/41.92MB
 443ba52fb7d8 Downloading [>                                                  ]  527.6kB/51.66MB
 dc193cc5b74f Downloading [=======>                                           ]  6.411MB/41.92MB
 dc193cc5b74f Downloading [========>                                          ]  6.837MB/41.92MB
 443ba52fb7d8 Downloading [=>                                                 ]  1.052MB/51.66MB
 443ba52fb7d8 Downloading [=>                                                 ]  1.571MB/51.66MB
 dc193cc5b74f Downloading [========>                                          ]  7.263MB/41.92MB
 dc193cc5b74f Downloading [=========>                                         ]  7.689MB/41.92MB
 dc193cc5b74f Downloading [=========>                                         ]  8.123MB/41.92MB
 443ba52fb7d8 Downloading [==>                                                ]  2.095MB/51.66MB
 443ba52fb7d8 Downloading [==>                                                ]   2.62MB/51.66MB
 dc193cc5b74f Downloading [==========>                                        ]  8.557MB/41.92MB
 443ba52fb7d8 Downloading [===>                                               ]  3.148MB/51.66MB
 dc193cc5b74f Downloading [==========>                                        ]  8.991MB/41.92MB
 443ba52fb7d8 Downloading [===>                                               ]  3.668MB/51.66MB
 dc193cc5b74f Downloading [===========>                                       ]  9.417MB/41.92MB
 6da9b68c8106 Downloading [=================>                                 ]     733B/2.084kB
 6da9b68c8106 Downloading [==================================================>]  2.084kB/2.084kB
 6da9b68c8106 Verifying Checksum
 6da9b68c8106 Download complete
 6da9b68c8106 Extracting [==================================================>]  2.084kB/2.084kB
 6da9b68c8106 Extracting [==================================================>]  2.084kB/2.084kB
 dc193cc5b74f Downloading [===========>                                       ]  9.839MB/41.92MB
 dc193cc5b74f Downloading [============>                                      ]  10.27MB/41.92MB
 443ba52fb7d8 Downloading [====>                                              ]  4.193MB/51.66MB
 443ba52fb7d8 Downloading [====>                                              ]  4.717MB/51.66MB
 443ba52fb7d8 Downloading [=====>                                             ]  5.245MB/51.66MB
 dc193cc5b74f Downloading [============>                                      ]  10.69MB/41.92MB
 6da9b68c8106 Pull complete
 dc193cc5b74f Downloading [=============>                                     ]  11.11MB/41.92MB
 dc193cc5b74f Downloading [=============>                                     ]  11.54MB/41.92MB
 443ba52fb7d8 Downloading [=====>                                             ]  5.774MB/51.66MB
 dc193cc5b74f Downloading [==============>                                    ]  11.97MB/41.92MB
 dc193cc5b74f Downloading [==============>                                    ]  12.39MB/41.92MB
 443ba52fb7d8 Downloading [======>                                            ]  6.306MB/51.66MB
 443ba52fb7d8 Downloading [======>                                            ]  6.834MB/51.66MB
 dc193cc5b74f Downloading [===============>                                   ]  12.81MB/41.92MB
 443ba52fb7d8 Downloading [=======>                                           ]  7.363MB/51.66MB
 dc193cc5b74f Downloading [================>                                  ]  13.67MB/41.92MB
 443ba52fb7d8 Downloading [=======>                                           ]  7.895MB/51.66MB
 dc193cc5b74f Downloading [================>                                  ]   14.1MB/41.92MB
 443ba52fb7d8 Downloading [========>                                          ]  8.415MB/51.66MB
 dc193cc5b74f Downloading [=================>                                 ]  14.52MB/41.92MB
 dc193cc5b74f Downloading [=================>                                 ]  14.95MB/41.92MB
 443ba52fb7d8 Downloading [========>                                          ]   8.94MB/51.66MB
 dc193cc5b74f Downloading [==================>                                ]  15.37MB/41.92MB
 dc193cc5b74f Downloading [==================>                                ]   15.8MB/41.92MB
 443ba52fb7d8 Downloading [=========>                                         ]  9.472MB/51.66MB
 dc193cc5b74f Downloading [===================>                               ]  16.22MB/41.92MB
 e43f206c86b8 Downloading [>                                                  ]  135.3kB/13.19MB
 443ba52fb7d8 Downloading [=========>                                         ]     10MB/51.66MB
 e43f206c86b8 Downloading [=>                                                 ]  278.5kB/13.19MB
 dc193cc5b74f Downloading [===================>                               ]  16.65MB/41.92MB
 e43f206c86b8 Downloading [==>                                                ]  573.4kB/13.19MB
 e43f206c86b8 Downloading [===>                                               ]  868.4kB/13.19MB
 dc193cc5b74f Downloading [====================>                              ]  17.07MB/41.92MB
 e43f206c86b8 Downloading [===>                                               ]  1.012MB/13.19MB
 dc193cc5b74f Downloading [====================>                              ]   17.5MB/41.92MB
 443ba52fb7d8 Downloading [==========>                                        ]  10.54MB/51.66MB
 e43f206c86b8 Downloading [====>                                              ]   1.16MB/13.19MB
 e43f206c86b8 Downloading [====>                                              ]  1.307MB/13.19MB
 dc193cc5b74f Downloading [=====================>                             ]  17.92MB/41.92MB
 e43f206c86b8 Downloading [======>                                            ]  1.602MB/13.19MB
 e43f206c86b8 Downloading [======>                                            ]   1.75MB/13.19MB
 e43f206c86b8 Downloading [=======>                                           ]  2.041MB/13.19MB
 443ba52fb7d8 Downloading [==========>                                        ]  11.06MB/51.66MB
 dc193cc5b74f Downloading [=====================>                             ]  18.35MB/41.92MB
 443ba52fb7d8 Downloading [===========>                                       ]  11.59MB/51.66MB
 e43f206c86b8 Downloading [=========>                                         ]  2.467MB/13.19MB
 443ba52fb7d8 Downloading [===========>                                       ]  12.11MB/51.66MB
 dc193cc5b74f Downloading [======================>                            ]  18.78MB/41.92MB
 e43f206c86b8 Downloading [==========>                                        ]  2.753MB/13.19MB
 e43f206c86b8 Downloading [===========>                                       ]  3.036MB/13.19MB
 dc193cc5b74f Downloading [======================>                            ]   19.2MB/41.92MB
 443ba52fb7d8 Downloading [============>                                      ]  12.64MB/51.66MB
 e43f206c86b8 Downloading [============>                                      ]  3.323MB/13.19MB
 e43f206c86b8 Downloading [=============>                                     ]  3.618MB/13.19MB
 dc193cc5b74f Downloading [=======================>                           ]  19.62MB/41.92MB
 e43f206c86b8 Downloading [==============>                                    ]  3.912MB/13.19MB
 dc193cc5b74f Downloading [=======================>                           ]  20.05MB/41.92MB
 443ba52fb7d8 Downloading [============>                                      ]  13.17MB/51.66MB
 443ba52fb7d8 Downloading [=============>                                     ]   13.7MB/51.66MB
 e43f206c86b8 Downloading [===============>                                   ]  4.207MB/13.19MB
 e43f206c86b8 Downloading [=================>                                 ]  4.502MB/13.19MB
 dc193cc5b74f Downloading [========================>                          ]  20.48MB/41.92MB
 443ba52fb7d8 Downloading [=============>                                     ]  14.22MB/51.66MB
 e43f206c86b8 Downloading [==================>                                ]  4.797MB/13.19MB
 dc193cc5b74f Downloading [========================>                          ]  20.91MB/41.92MB
 e43f206c86b8 Downloading [===================>                               ]  5.092MB/13.19MB
 dc193cc5b74f Downloading [=========================>                         ]  21.34MB/41.92MB
 443ba52fb7d8 Downloading [==============>                                    ]  14.74MB/51.66MB
 443ba52fb7d8 Downloading [==============>                                    ]  15.26MB/51.66MB
 e43f206c86b8 Downloading [====================>                              ]   5.53MB/13.19MB
 dc193cc5b74f Downloading [=========================>                         ]  21.76MB/41.92MB
 e43f206c86b8 Downloading [======================>                            ]  5.809MB/13.19MB
 e43f206c86b8 Downloading [=======================>                           ]  6.104MB/13.19MB
 dc193cc5b74f Downloading [==========================>                        ]  22.19MB/41.92MB
 443ba52fb7d8 Downloading [===============>                                   ]  15.79MB/51.66MB
 e43f206c86b8 Downloading [========================>                          ]  6.399MB/13.19MB
 443ba52fb7d8 Downloading [===============>                                   ]  16.31MB/51.66MB
 dc193cc5b74f Downloading [==========================>                        ]  22.62MB/41.92MB
 e43f206c86b8 Downloading [=========================>                         ]  6.694MB/13.19MB
 443ba52fb7d8 Downloading [================>                                  ]  16.84MB/51.66MB
 e43f206c86b8 Downloading [==========================>                        ]  6.989MB/13.19MB
 dc193cc5b74f Downloading [===========================>                       ]  23.05MB/41.92MB
 e43f206c86b8 Downloading [===========================>                       ]  7.283MB/13.19MB
 dc193cc5b74f Downloading [============================>                      ]  23.49MB/41.92MB
 e43f206c86b8 Downloading [=============================>                     ]  7.726MB/13.19MB
 dc193cc5b74f Downloading [============================>                      ]  23.91MB/41.92MB
 e43f206c86b8 Downloading [==============================>                    ]  8.013MB/13.19MB
 443ba52fb7d8 Downloading [================>                                  ]  17.37MB/51.66MB
 443ba52fb7d8 Downloading [=================>                                 ]   17.9MB/51.66MB
 e43f206c86b8 Downloading [===============================>                   ]  8.307MB/13.19MB
 443ba52fb7d8 Downloading [=================>                                 ]  18.43MB/51.66MB
 dc193cc5b74f Downloading [=============================>                     ]  24.34MB/41.92MB
 e43f206c86b8 Downloading [================================>                  ]  8.594MB/13.19MB
 dc193cc5b74f Downloading [=============================>                     ]  24.76MB/41.92MB
 e43f206c86b8 Downloading [=================================>                 ]  8.889MB/13.19MB
 443ba52fb7d8 Downloading [==================>                                ]  18.95MB/51.66MB
 443ba52fb7d8 Downloading [==================>                                ]  19.47MB/51.66MB
 dc193cc5b74f Downloading [==============================>                    ]  25.18MB/41.92MB
 e43f206c86b8 Downloading [===================================>               ]  9.331MB/13.19MB
 e43f206c86b8 Downloading [===================================>               ]  9.479MB/13.19MB
 e43f206c86b8 Downloading [=====================================>             ]  9.766MB/13.19MB
 dc193cc5b74f Downloading [==============================>                    ]  25.61MB/41.92MB
 443ba52fb7d8 Downloading [===================>                               ]     20MB/51.66MB
 e43f206c86b8 Downloading [=====================================>             ]  9.901MB/13.19MB
 e43f206c86b8 Downloading [======================================>            ]  10.05MB/13.19MB
 e43f206c86b8 Downloading [======================================>            ]  10.18MB/13.19MB
 dc193cc5b74f Downloading [===============================>                   ]  26.03MB/41.92MB
 e43f206c86b8 Downloading [=======================================>           ]  10.33MB/13.19MB
 443ba52fb7d8 Downloading [===================>                               ]  20.53MB/51.66MB
 e43f206c86b8 Downloading [========================================>          ]  10.63MB/13.19MB
 dc193cc5b74f Downloading [===============================>                   ]  26.46MB/41.92MB
 e43f206c86b8 Downloading [=========================================>         ]  10.91MB/13.19MB
 e43f206c86b8 Downloading [=========================================>         ]  11.06MB/13.19MB
 dc193cc5b74f Downloading [================================>                  ]  26.88MB/41.92MB
 e43f206c86b8 Downloading [===========================================>       ]  11.35MB/13.19MB
 dc193cc5b74f Downloading [================================>                  ]  27.31MB/41.92MB
 443ba52fb7d8 Downloading [====================>                              ]  21.05MB/51.66MB
 443ba52fb7d8 Downloading [====================>                              ]  21.58MB/51.66MB
 e43f206c86b8 Downloading [============================================>      ]  11.65MB/13.19MB
 443ba52fb7d8 Downloading [=====================>                             ]   22.1MB/51.66MB
 e43f206c86b8 Downloading [=============================================>     ]  11.94MB/13.19MB
 dc193cc5b74f Downloading [=================================>                 ]  27.74MB/41.92MB
 e43f206c86b8 Downloading [==============================================>    ]  12.23MB/13.19MB
 443ba52fb7d8 Downloading [=====================>                             ]  22.62MB/51.66MB
 dc193cc5b74f Downloading [=================================>                 ]  28.17MB/41.92MB
 443ba52fb7d8 Downloading [======================>                            ]  23.16MB/51.66MB
 e43f206c86b8 Downloading [===============================================>   ]  12.65MB/13.19MB
 dc193cc5b74f Downloading [==================================>                ]   28.6MB/41.92MB
 e43f206c86b8 Downloading [=================================================> ]  13.09MB/13.19MB
 e43f206c86b8 Verifying Checksum
 e43f206c86b8 Download complete
 e43f206c86b8 Extracting [>                                                  ]  163.8kB/13.19MB
 443ba52fb7d8 Downloading [======================>                            ]  23.68MB/51.66MB
 dc193cc5b74f Downloading [==================================>                ]  29.02MB/41.92MB
 dc193cc5b74f Downloading [===================================>               ]  29.46MB/41.92MB
 e43f206c86b8 Extracting [=>                                                 ]  327.7kB/13.19MB
 443ba52fb7d8 Downloading [=======================>                           ]   24.2MB/51.66MB
 443ba52fb7d8 Downloading [=======================>                           ]  24.73MB/51.66MB
 dc193cc5b74f Downloading [===================================>               ]  29.88MB/41.92MB
 e43f206c86b8 Extracting [=>                                                 ]  491.5kB/13.19MB
 443ba52fb7d8 Downloading [========================>                          ]  25.25MB/51.66MB
 dc193cc5b74f Downloading [====================================>              ]  30.73MB/41.92MB
 e43f206c86b8 Extracting [=====>                                             ]  1.475MB/13.19MB
 443ba52fb7d8 Downloading [========================>                          ]  25.77MB/51.66MB
 e43f206c86b8 Extracting [==========>                                        ]  2.785MB/13.19MB
 dc193cc5b74f Downloading [=====================================>             ]  31.15MB/41.92MB
 443ba52fb7d8 Downloading [=========================>                         ]   26.3MB/51.66MB
 e43f206c86b8 Extracting [==============>                                    ]  3.768MB/13.19MB
 dc193cc5b74f Downloading [======================================>            ]  32.01MB/41.92MB
 443ba52fb7d8 Downloading [=========================>                         ]  26.82MB/51.66MB
 e43f206c86b8 Extracting [==================>                                ]  4.751MB/13.19MB
 dc193cc5b74f Downloading [======================================>            ]  32.45MB/41.92MB
 443ba52fb7d8 Downloading [==========================>                        ]  27.34MB/51.66MB
 e43f206c86b8 Extracting [=====================>                             ]  5.571MB/13.19MB
 b0faedef9ffa Downloading [====================================>              ]     722B/990B
 b0faedef9ffa Downloading [==================================================>]     990B/990B
 b0faedef9ffa Verifying Checksum
 b0faedef9ffa Download complete
 dc193cc5b74f Downloading [=======================================>           ]  32.87MB/41.92MB
 e43f206c86b8 Extracting [========================>                          ]  6.554MB/13.19MB
 443ba52fb7d8 Downloading [==========================>                        ]  27.86MB/51.66MB
 dc193cc5b74f Downloading [=======================================>           ]   33.3MB/41.92MB
 e43f206c86b8 Extracting [==========================>                        ]  7.045MB/13.19MB
 443ba52fb7d8 Downloading [===========================>                       ]  28.39MB/51.66MB
 e43f206c86b8 Extracting [=============================>                     ]  7.864MB/13.19MB
 dc193cc5b74f Downloading [========================================>          ]  34.16MB/41.92MB
 e43f206c86b8 Extracting [=================================>                 ]  8.847MB/13.19MB
 443ba52fb7d8 Downloading [===========================>                       ]  28.92MB/51.66MB
 e43f206c86b8 Extracting [=====================================>             ]   9.83MB/13.19MB
 443ba52fb7d8 Downloading [============================>                      ]  29.44MB/51.66MB
 dc193cc5b74f Downloading [=========================================>         ]  35.02MB/41.92MB
 e43f206c86b8 Extracting [=======================================>           ]  10.49MB/13.19MB
 dc193cc5b74f Downloading [==========================================>        ]  35.44MB/41.92MB
 e43f206c86b8 Extracting [==========================================>        ]   11.3MB/13.19MB
 443ba52fb7d8 Downloading [============================>                      ]  29.96MB/51.66MB
 443ba52fb7d8 Downloading [=============================>                     ]  30.48MB/51.66MB
 e43f206c86b8 Extracting [=============================================>     ]  12.12MB/13.19MB
 443ba52fb7d8 Downloading [=============================>                     ]     31MB/51.66MB
 dc193cc5b74f Downloading [===========================================>       ]  36.29MB/41.92MB
 e43f206c86b8 Extracting [===============================================>   ]  12.45MB/13.19MB
 dc193cc5b74f Downloading [===========================================>       ]  36.73MB/41.92MB
 443ba52fb7d8 Downloading [==============================>                    ]  31.53MB/51.66MB
 e43f206c86b8 Extracting [===============================================>   ]  12.62MB/13.19MB
 dc193cc5b74f Downloading [============================================>      ]  37.16MB/41.92MB
 e43f206c86b8 Extracting [=================================================> ]  13.11MB/13.19MB
 443ba52fb7d8 Downloading [===============================>                   ]  32.05MB/51.66MB
 dc193cc5b74f Downloading [============================================>      ]  37.58MB/41.92MB
 443ba52fb7d8 Downloading [===============================>                   ]  32.57MB/51.66MB
 dc193cc5b74f Downloading [=============================================>     ]  38.43MB/41.92MB
 e43f206c86b8 Extracting [==================================================>]  13.19MB/13.19MB
 dc193cc5b74f Downloading [==============================================>    ]  38.86MB/41.92MB
 a77c018aa078 Downloading [>                                                  ]  537.3kB/68.71MB
 dc193cc5b74f Downloading [==============================================>    ]  39.29MB/41.92MB
 443ba52fb7d8 Downloading [================================>                  ]  33.09MB/51.66MB
 dc193cc5b74f Downloading [===============================================>   ]  39.72MB/41.92MB
 dc193cc5b74f Downloading [===============================================>   ]  40.15MB/41.92MB
 e43f206c86b8 Pull complete
 b0faedef9ffa Extracting [==================================================>]     990B/990B
 b0faedef9ffa Extracting [==================================================>]     990B/990B
 443ba52fb7d8 Downloading [================================>                  ]  33.62MB/51.66MB
 443ba52fb7d8 Downloading [=================================>                 ]  34.14MB/51.66MB
 a77c018aa078 Downloading [>                                                  ]  1.078MB/68.71MB
 dc193cc5b74f Downloading [================================================>  ]  40.58MB/41.92MB
 dc193cc5b74f Downloading [================================================>  ]  41.01MB/41.92MB
 dc193cc5b74f Downloading [=================================================> ]  41.44MB/41.92MB
 a77c018aa078 Downloading [=>                                                 ]   1.61MB/68.71MB
 dc193cc5b74f Downloading [=================================================> ]  41.87MB/41.92MB
 443ba52fb7d8 Downloading [=================================>                 ]  34.67MB/51.66MB
 443ba52fb7d8 Downloading [==================================>                ]  35.19MB/51.66MB
 b0faedef9ffa Pull complete
 dc193cc5b74f Verifying Checksum
 dc193cc5b74f Download complete
 a77c018aa078 Downloading [=>                                                 ]  2.139MB/68.71MB
 dc193cc5b74f Extracting [>                                                  ]    426kB/41.92MB
 443ba52fb7d8 Downloading [==================================>                ]  35.72MB/51.66MB
 a77c018aa078 Downloading [=>                                                 ]  2.667MB/68.71MB
 dc193cc5b74f Extracting [==>                                                ]  1.704MB/41.92MB
 dc193cc5b74f Extracting [====>                                              ]  3.408MB/41.92MB
 dc193cc5b74f Extracting [======>                                            ]  5.538MB/41.92MB
 a77c018aa078 Downloading [==>                                                ]  3.728MB/68.71MB
 dc193cc5b74f Extracting [========>                                          ]  7.242MB/41.92MB
 443ba52fb7d8 Downloading [===================================>               ]  36.24MB/51.66MB
 443ba52fb7d8 Downloading [===================================>               ]  36.76MB/51.66MB
 a77c018aa078 Downloading [===>                                               ]  4.797MB/68.71MB
 dc193cc5b74f Extracting [==========>                                        ]  8.946MB/41.92MB
 dc193cc5b74f Extracting [=============>                                     ]  11.08MB/41.92MB
 a77c018aa078 Downloading [====>                                              ]  5.866MB/68.71MB
 443ba52fb7d8 Downloading [====================================>              ]  37.28MB/51.66MB
 443ba52fb7d8 Downloading [====================================>              ]  37.81MB/51.66MB
 dc193cc5b74f Extracting [================>                                  ]  13.63MB/41.92MB
 a77c018aa078 Downloading [=====>                                             ]  6.939MB/68.71MB
 dc193cc5b74f Extracting [=================>                                 ]  14.91MB/41.92MB
 443ba52fb7d8 Downloading [=====================================>             ]  38.33MB/51.66MB
 dc193cc5b74f Extracting [===================>                               ]  16.61MB/41.92MB
 a77c018aa078 Downloading [=====>                                             ]  8.013MB/68.71MB
 613ded3f7b83 Downloading [==================================================>]     146B/146B
 613ded3f7b83 Download complete
 a77c018aa078 Downloading [======>                                            ]  8.549MB/68.71MB
 dc193cc5b74f Extracting [=====================>                             ]  18.32MB/41.92MB
 dc193cc5b74f Extracting [========================>                          ]  20.45MB/41.92MB
 443ba52fb7d8 Downloading [=====================================>             ]  38.86MB/51.66MB
 443ba52fb7d8 Downloading [======================================>            ]  39.91MB/51.66MB
 a77c018aa078 Downloading [=======>                                           ]  9.622MB/68.71MB
 dc193cc5b74f Extracting [==========================>                        ]  22.58MB/41.92MB
 dc193cc5b74f Extracting [============================>                      ]  23.86MB/41.92MB
 a77c018aa078 Downloading [=======>                                           ]  10.69MB/68.71MB
 443ba52fb7d8 Downloading [=======================================>           ]  40.96MB/51.66MB
 443ba52fb7d8 Downloading [========================================>          ]  41.48MB/51.66MB
 dc193cc5b74f Extracting [==============================>                    ]  25.99MB/41.92MB
 a77c018aa078 Downloading [========>                                          ]  11.22MB/68.71MB
 dc193cc5b74f Extracting [================================>                  ]  27.26MB/41.92MB
 a77c018aa078 Downloading [========>                                          ]  12.29MB/68.71MB
 dc193cc5b74f Extracting [==================================>                ]  28.97MB/41.92MB
 443ba52fb7d8 Downloading [========================================>          ]  42.01MB/51.66MB
 443ba52fb7d8 Downloading [=========================================>         ]  42.54MB/51.66MB
 a77c018aa078 Downloading [=========>                                         ]  12.82MB/68.71MB
 dc193cc5b74f Extracting [=====================================>             ]   31.1MB/41.92MB
 dc193cc5b74f Extracting [=======================================>           ]   32.8MB/41.92MB
 dc193cc5b74f Extracting [=========================================>         ]  34.93MB/41.92MB
 a77c018aa078 Downloading [==========>                                        ]   13.9MB/68.71MB
 dc193cc5b74f Extracting [============================================>      ]  37.49MB/41.92MB
 dc193cc5b74f Extracting [===============================================>   ]  39.62MB/41.92MB
 a77c018aa078 Downloading [==========>                                        ]  14.44MB/68.71MB
 dc193cc5b74f Extracting [=================================================> ]  41.32MB/41.92MB
 dc193cc5b74f Extracting [==================================================>]  41.92MB/41.92MB
 443ba52fb7d8 Downloading [==========================================>        ]  43.59MB/51.66MB
 443ba52fb7d8 Downloading [==========================================>        ]  44.11MB/51.66MB
 443ba52fb7d8 Downloading [===========================================>       ]  44.64MB/51.66MB
 a77c018aa078 Downloading [==========>                                        ]  14.96MB/68.71MB
 dc193cc5b74f Pull complete
 a77c018aa078 Downloading [===========>                                       ]   15.5MB/68.71MB
 944e9862aa5e Extracting [>                                                  ]  65.54kB/4.749MB
 443ba52fb7d8 Downloading [===========================================>       ]  45.16MB/51.66MB
 443ba52fb7d8 Downloading [============================================>      ]  45.69MB/51.66MB
 a77c018aa078 Downloading [===========>                                       ]  16.04MB/68.71MB
 944e9862aa5e Extracting [==>                                                ]  262.1kB/4.749MB
 944e9862aa5e Extracting [=============>                                     ]  1.245MB/4.749MB
 443ba52fb7d8 Downloading [============================================>      ]  46.22MB/51.66MB
 443ba52fb7d8 Downloading [=============================================>     ]  47.27MB/51.66MB
 a77c018aa078 Downloading [============>                                      ]  17.12MB/68.71MB
 944e9862aa5e Extracting [========================>                          ]  2.294MB/4.749MB
 bd9ddc54bea9 Downloading [==================================================>]      34B/34B
 bd9ddc54bea9 Verifying Checksum
 bd9ddc54bea9 Download complete
 a77c018aa078 Downloading [============>                                      ]  17.66MB/68.71MB
 944e9862aa5e Extracting [========================================>          ]  3.867MB/4.749MB
 944e9862aa5e Extracting [==================================================>]  4.749MB/4.749MB
 a77c018aa078 Downloading [=============>                                     ]   18.2MB/68.71MB
 944e9862aa5e Pull complete
 443ba52fb7d8 Downloading [==============================================>    ]  48.33MB/51.66MB
 443ba52fb7d8 Downloading [===============================================>   ]  49.38MB/51.66MB
 a77c018aa078 Downloading [==============>                                    ]  19.25MB/68.71MB
 grocery-items-management-api-gateway Pulled
 a77c018aa078 Downloading [==============>                                    ]  19.79MB/68.71MB
 443ba52fb7d8 Downloading [================================================>  ]  50.43MB/51.66MB
 443ba52fb7d8 Downloading [=================================================> ]  51.48MB/51.66MB
 a77c018aa078 Downloading [===============>                                   ]  20.86MB/68.71MB
 443ba52fb7d8 Verifying Checksum
 443ba52fb7d8 Download complete
 443ba52fb7d8 Extracting [>                                                  ]  524.3kB/51.66MB
 a7297f4b08c3 Downloading [===================>                               ]     733B/1.873kB
 a7297f4b08c3 Downloading [==================================================>]  1.873kB/1.873kB
 a7297f4b08c3 Verifying Checksum
 a7297f4b08c3 Download complete
 a77c018aa078 Downloading [===============>                                   ]  21.93MB/68.71MB
 443ba52fb7d8 Extracting [=>                                                 ]  1.573MB/51.66MB
 a77c018aa078 Downloading [================>                                  ]     23MB/68.71MB
 443ba52fb7d8 Extracting [===>                                               ]  3.146MB/51.66MB
 a77c018aa078 Downloading [=================>                                 ]  23.54MB/68.71MB
 443ba52fb7d8 Extracting [====>                                              ]  4.719MB/51.66MB
 a77c018aa078 Downloading [=================>                                 ]  24.08MB/68.71MB
 443ba52fb7d8 Extracting [=====>                                             ]  5.767MB/51.66MB
 a77c018aa078 Downloading [==================>                                ]  25.15MB/68.71MB
 a77c018aa078 Downloading [===================>                               ]  26.22MB/68.71MB
 a77c018aa078 Downloading [===================>                               ]  26.76MB/68.71MB
 443ba52fb7d8 Extracting [======>                                            ]  6.291MB/51.66MB
 443ba52fb7d8 Extracting [======>                                            ]  6.816MB/51.66MB
 443ba52fb7d8 Extracting [=======>                                           ]   7.34MB/51.66MB
 a77c018aa078 Downloading [===================>                               ]  27.29MB/68.71MB
 443ba52fb7d8 Extracting [========>                                          ]  8.389MB/51.66MB
 a77c018aa078 Downloading [====================>                              ]  27.82MB/68.71MB
 443ba52fb7d8 Extracting [========>                                          ]  8.913MB/51.66MB
 443ba52fb7d8 Extracting [=========>                                         ]  9.437MB/51.66MB
 443ba52fb7d8 Extracting [==========>                                        ]  11.01MB/51.66MB
 a77c018aa078 Downloading [====================>                              ]  28.35MB/68.71MB
 a77c018aa078 Downloading [=====================>                             ]  28.89MB/68.71MB
 443ba52fb7d8 Extracting [===========>                                       ]  12.06MB/51.66MB
 443ba52fb7d8 Extracting [============>                                      ]  13.11MB/51.66MB
 a77c018aa078 Downloading [=====================>                             ]  29.42MB/68.71MB
 a77c018aa078 Downloading [=====================>                             ]  29.96MB/68.71MB
 443ba52fb7d8 Extracting [=============>                                     ]  13.63MB/51.66MB
 443ba52fb7d8 Extracting [=============>                                     ]  14.16MB/51.66MB
 a77c018aa078 Downloading [======================>                            ]   30.5MB/68.71MB
 443ba52fb7d8 Extracting [==============>                                    ]  14.68MB/51.66MB
 a77c018aa078 Downloading [======================>                            ]  31.04MB/68.71MB
 443ba52fb7d8 Extracting [===============>                                   ]  15.73MB/51.66MB
 a77c018aa078 Downloading [=======================>                           ]  32.11MB/68.71MB
 a77c018aa078 Downloading [=======================>                           ]  32.65MB/68.71MB
 443ba52fb7d8 Extracting [===============>                                   ]  16.25MB/51.66MB
 443ba52fb7d8 Extracting [================>                                  ]  16.78MB/51.66MB
 a77c018aa078 Downloading [========================>                          ]  33.19MB/68.71MB
 443ba52fb7d8 Extracting [=================>                                 ]  17.83MB/51.66MB
 a77c018aa078 Downloading [========================>                          ]  34.27MB/68.71MB
 443ba52fb7d8 Extracting [==================>                                ]  18.87MB/51.66MB
 a77c018aa078 Downloading [=========================>                         ]  35.34MB/68.71MB
 a77c018aa078 Downloading [==========================>                        ]  35.88MB/68.71MB
 443ba52fb7d8 Extracting [==================>                                ]   19.4MB/51.66MB
 a77c018aa078 Downloading [==========================>                        ]  36.42MB/68.71MB
 443ba52fb7d8 Extracting [===================>                               ]  20.45MB/51.66MB
 443ba52fb7d8 Extracting [====================>                              ]  20.97MB/51.66MB
 a77c018aa078 Downloading [==========================>                        ]  36.96MB/68.71MB
 a77c018aa078 Downloading [===========================>                       ]   37.5MB/68.71MB
 a77c018aa078 Downloading [===========================>                       ]  38.03MB/68.71MB
 a77c018aa078 Downloading [============================>                      ]  38.57MB/68.71MB
 443ba52fb7d8 Extracting [====================>                              ]   21.5MB/51.66MB
 a77c018aa078 Downloading [============================>                      ]  39.11MB/68.71MB
 a77c018aa078 Downloading [============================>                      ]  39.65MB/68.71MB
 a77c018aa078 Downloading [=============================>                     ]  40.18MB/68.71MB
 a77c018aa078 Downloading [=============================>                     ]  40.72MB/68.71MB
 443ba52fb7d8 Extracting [=====================>                             ]  22.02MB/51.66MB
 a77c018aa078 Downloading [==============================>                    ]  41.26MB/68.71MB
 a77c018aa078 Downloading [==============================>                    ]  41.79MB/68.71MB
 443ba52fb7d8 Extracting [=====================>                             ]  22.54MB/51.66MB
 443ba52fb7d8 Extracting [======================>                            ]  23.07MB/51.66MB
 443ba52fb7d8 Extracting [=======================>                           ]  24.12MB/51.66MB
 a77c018aa078 Downloading [==============================>                    ]  42.33MB/68.71MB
 443ba52fb7d8 Extracting [========================>                          ]  25.17MB/51.66MB
 443ba52fb7d8 Extracting [=========================>                         ]  26.74MB/51.66MB
 443ba52fb7d8 Extracting [==========================>                        ]  27.79MB/51.66MB
 a77c018aa078 Downloading [===============================>                   ]  42.87MB/68.71MB
 a77c018aa078 Downloading [===============================>                   ]  43.41MB/68.71MB
 443ba52fb7d8 Extracting [===========================>                       ]  28.84MB/51.66MB
 443ba52fb7d8 Extracting [============================>                      ]  29.88MB/51.66MB
 443ba52fb7d8 Extracting [=============================>                     ]  30.93MB/51.66MB
 a77c018aa078 Downloading [===============================>                   ]  43.95MB/68.71MB
 a77c018aa078 Downloading [================================>                  ]  44.48MB/68.71MB
 443ba52fb7d8 Extracting [===============================>                   ]  32.51MB/51.66MB
 a77c018aa078 Downloading [================================>                  ]  45.02MB/68.71MB
 a77c018aa078 Downloading [=================================>                 ]  45.56MB/68.71MB
 a77c018aa078 Downloading [=================================>                 ]  46.09MB/68.71MB
 a77c018aa078 Downloading [==================================>                ]  47.17MB/68.71MB
 a77c018aa078 Downloading [==================================>                ]  47.69MB/68.71MB
 a77c018aa078 Downloading [===================================>               ]  48.24MB/68.71MB
 a77c018aa078 Downloading [===================================>               ]  48.77MB/68.71MB
 443ba52fb7d8 Extracting [===============================>                   ]  33.03MB/51.66MB
 443ba52fb7d8 Extracting [================================>                  ]  33.55MB/51.66MB
 a77c018aa078 Downloading [===================================>               ]  49.31MB/68.71MB
 443ba52fb7d8 Extracting [=================================>                 ]   34.6MB/51.66MB
 a77c018aa078 Downloading [====================================>              ]  50.38MB/68.71MB
 443ba52fb7d8 Extracting [==================================>                ]  35.65MB/51.66MB
 a77c018aa078 Downloading [=====================================>             ]  50.92MB/68.71MB
 443ba52fb7d8 Extracting [===================================>               ]  36.18MB/51.66MB
 a77c018aa078 Downloading [=====================================>             ]  51.46MB/68.71MB
 a77c018aa078 Downloading [======================================>            ]  52.54MB/68.71MB
 a77c018aa078 Downloading [======================================>            ]  53.08MB/68.71MB
 443ba52fb7d8 Extracting [===================================>               ]   36.7MB/51.66MB
 443ba52fb7d8 Extracting [====================================>              ]  37.22MB/51.66MB
 a77c018aa078 Downloading [=======================================>           ]  53.61MB/68.71MB
 a77c018aa078 Downloading [=======================================>           ]  54.67MB/68.71MB
 a77c018aa078 Downloading [========================================>          ]   55.2MB/68.71MB
 443ba52fb7d8 Extracting [====================================>              ]  37.75MB/51.66MB
 a77c018aa078 Downloading [========================================>          ]  56.27MB/68.71MB
 443ba52fb7d8 Extracting [=====================================>             ]  38.27MB/51.66MB
 a77c018aa078 Downloading [=========================================>         ]  57.34MB/68.71MB
 a77c018aa078 Downloading [==========================================>        ]  58.41MB/68.71MB
 443ba52fb7d8 Extracting [=====================================>             ]   38.8MB/51.66MB
 443ba52fb7d8 Extracting [======================================>            ]  39.32MB/51.66MB
 a77c018aa078 Downloading [===========================================>       ]  59.47MB/68.71MB
 a77c018aa078 Downloading [============================================>      ]  60.54MB/68.71MB
 443ba52fb7d8 Extracting [=======================================>           ]  40.37MB/51.66MB
 a77c018aa078 Downloading [============================================>      ]  61.61MB/68.71MB
 443ba52fb7d8 Extracting [=======================================>           ]  40.89MB/51.66MB
 a77c018aa078 Downloading [=============================================>     ]  62.14MB/68.71MB
 443ba52fb7d8 Extracting [========================================>          ]  41.42MB/51.66MB
 a77c018aa078 Downloading [==============================================>    ]  63.21MB/68.71MB
 a77c018aa078 Downloading [==============================================>    ]  64.28MB/68.71MB
 443ba52fb7d8 Extracting [========================================>          ]  41.94MB/51.66MB
 a77c018aa078 Downloading [===============================================>   ]  65.36MB/68.71MB
 443ba52fb7d8 Extracting [=========================================>         ]  42.47MB/51.66MB
 a77c018aa078 Downloading [================================================>  ]  66.42MB/68.71MB
 443ba52fb7d8 Extracting [==========================================>        ]  43.52MB/51.66MB
 a77c018aa078 Downloading [================================================>  ]  66.95MB/68.71MB
 443ba52fb7d8 Extracting [==========================================>        ]  44.04MB/51.66MB
 443ba52fb7d8 Extracting [===========================================>       ]  45.09MB/51.66MB
 a77c018aa078 Downloading [=================================================> ]  68.02MB/68.71MB
 443ba52fb7d8 Extracting [=============================================>     ]  46.66MB/51.66MB
 a77c018aa078 Downloading [=================================================> ]  68.55MB/68.71MB
 a77c018aa078 Verifying Checksum
 a77c018aa078 Download complete
 a77c018aa078 Extracting [>                                                  ]  557.1kB/68.71MB
 443ba52fb7d8 Extracting [=============================================>     ]  47.19MB/51.66MB
 a77c018aa078 Extracting [=>                                                 ]  2.228MB/68.71MB
 a77c018aa078 Extracting [==>                                                ]  3.342MB/68.71MB
 443ba52fb7d8 Extracting [==============================================>    ]  47.71MB/51.66MB
 a77c018aa078 Extracting [===>                                               ]  4.456MB/68.71MB
 a77c018aa078 Extracting [====>                                              ]  5.571MB/68.71MB
 443ba52fb7d8 Extracting [==============================================>    ]  48.23MB/51.66MB
 a77c018aa078 Extracting [====>                                              ]  6.685MB/68.71MB
 443ba52fb7d8 Extracting [===============================================>   ]  48.76MB/51.66MB
 a77c018aa078 Extracting [=====>                                             ]  7.799MB/68.71MB
 a77c018aa078 Extracting [======>                                            ]  8.913MB/68.71MB
 443ba52fb7d8 Extracting [===============================================>   ]  49.28MB/51.66MB
 a77c018aa078 Extracting [=======>                                           ]  10.03MB/68.71MB
 a77c018aa078 Extracting [========>                                          ]  11.14MB/68.71MB
 a77c018aa078 Extracting [========>                                          ]  12.26MB/68.71MB
 a77c018aa078 Extracting [=========>                                         ]  13.37MB/68.71MB
 a77c018aa078 Extracting [==========>                                        ]  14.48MB/68.71MB
 a77c018aa078 Extracting [===========>                                       ]   15.6MB/68.71MB
 443ba52fb7d8 Extracting [================================================>  ]  49.81MB/51.66MB
 a77c018aa078 Extracting [============>                                      ]  16.71MB/68.71MB
 443ba52fb7d8 Extracting [================================================>  ]  50.33MB/51.66MB
 a77c018aa078 Extracting [============>                                      ]  17.83MB/68.71MB
 a77c018aa078 Extracting [=============>                                     ]  18.38MB/68.71MB
 443ba52fb7d8 Extracting [=================================================> ]  50.86MB/51.66MB
 a77c018aa078 Extracting [=============>                                     ]  18.94MB/68.71MB
 a77c018aa078 Extracting [==============>                                    ]   19.5MB/68.71MB
 443ba52fb7d8 Extracting [=================================================> ]  51.38MB/51.66MB
 a77c018aa078 Extracting [==============>                                    ]  20.61MB/68.71MB
 a77c018aa078 Extracting [===============>                                   ]  21.73MB/68.71MB
 a77c018aa078 Extracting [================>                                  ]  22.84MB/68.71MB
 a77c018aa078 Extracting [=================>                                 ]   23.4MB/68.71MB
 a77c018aa078 Extracting [=================>                                 ]  24.51MB/68.71MB
 443ba52fb7d8 Extracting [==================================================>]  51.66MB/51.66MB
 a77c018aa078 Extracting [==================>                                ]  25.62MB/68.71MB
 a77c018aa078 Extracting [===================>                               ]  26.18MB/68.71MB
 a77c018aa078 Extracting [====================>                              ]  27.85MB/68.71MB
 a77c018aa078 Extracting [=====================>                             ]  30.08MB/68.71MB
 a77c018aa078 Extracting [=======================>                           ]  32.31MB/68.71MB
 a77c018aa078 Extracting [========================>                          ]  33.42MB/68.71MB
 443ba52fb7d8 Pull complete
 a77c018aa078 Extracting [=========================>                         ]  34.54MB/68.71MB
 redis Pulled
 a77c018aa078 Extracting [=========================>                         ]  35.65MB/68.71MB
 a77c018aa078 Extracting [===========================>                       ]  37.32MB/68.71MB
 a77c018aa078 Extracting [=============================>                     ]  40.67MB/68.71MB
 a77c018aa078 Extracting [================================>                  ]  44.01MB/68.71MB
 a77c018aa078 Extracting [==================================>                ]  46.79MB/68.71MB
 a77c018aa078 Extracting [====================================>              ]  49.58MB/68.71MB
 a77c018aa078 Extracting [======================================>            ]  52.92MB/68.71MB
 a77c018aa078 Extracting [========================================>          ]  55.71MB/68.71MB
 a77c018aa078 Extracting [==========================================>        ]  59.05MB/68.71MB
 a77c018aa078 Extracting [=============================================>     ]  62.39MB/68.71MB
 a77c018aa078 Extracting [===============================================>   ]  65.73MB/68.71MB
 a77c018aa078 Extracting [=================================================> ]   67.4MB/68.71MB
 a77c018aa078 Extracting [=================================================> ]  67.96MB/68.71MB
 a77c018aa078 Extracting [=================================================> ]  68.52MB/68.71MB
 a77c018aa078 Extracting [==================================================>]  68.71MB/68.71MB
 a77c018aa078 Pull complete
 613ded3f7b83 Extracting [==================================================>]     146B/146B
 613ded3f7b83 Extracting [==================================================>]     146B/146B
 613ded3f7b83 Pull complete
 bd9ddc54bea9 Extracting [==================================================>]      34B/34B
 bd9ddc54bea9 Extracting [==================================================>]      34B/34B
 bd9ddc54bea9 Pull complete
 a7297f4b08c3 Extracting [==================================================>]  1.873kB/1.873kB
 a7297f4b08c3 Extracting [==================================================>]  1.873kB/1.873kB
 a7297f4b08c3 Pull complete
 consul-server Pulled
 Network docker-compose_grocery-items-management-microservices  Creating
 Network docker-compose_grocery-items-management-microservices  Created
 Container consul-server  Creating
 Container redis  Creating
 Container zipkin  Creating
 Container zipkin  Created
 Container redis  Created
 Container consul-server  Created
 Container grocery-items-management  Creating
 Container consul-client  Creating
 Container grocery-items-management  Created
 Container grocery-items-management-api-gateway  Creating
 Container consul-client  Created
 Container grocery-items-management-api-gateway  Created
 Container consul-server  Starting
 Container zipkin  Starting
 Container redis  Starting
 Container redis  Started
 Container zipkin  Started
 Container consul-server  Started
 Container grocery-items-management  Starting
 Container consul-client  Starting
 Container grocery-items-management  Started
 Container grocery-items-management-api-gateway  Starting
 Container consul-client  Started
 Container grocery-items-management-api-gateway  Started

```

# Microservice Undeploy from Localhost

```bash

Lyes Sefiane@******** ~/Documents/eclipse-workspace/deployments/grocery-items-management-microservices-deployment (main)
$ ./grocery-items-management-microservices


  ┏┓             ┳
  ┃┓┏┓┏┓┏┏┓┏┓┓┏  ┃╋┏┓┏┳┓┏
  ┗┛┛ ┗┛┗┗ ┛ ┗┫  ┻┗┗ ┛┗┗┛
  ┳┳┓         ┛          ┳┳┓•            •
  ┃┃┃┏┓┏┓┏┓┏┓┏┓┏┳┓┏┓┏┓╋  ┃┃┃┓┏┏┓┏┓┏┏┓┏┓┓┏┓┏┏┓
  ┛ ┗┗┻┛┗┗┻┗┫┗ ┛┗┗┗ ┛┗┗  ┛ ┗┗┗┛ ┗┛┛┗ ┛ ┗┛┗┗┗
            ┛


MINGW64_NT-10.0-19045 : Hi 😊 ! please make a selection.

1) Start Microservice
2) ShutDown Microservice
3) quit
#? 2
ShutDown Start Grocery Items Management Microservice ...
 Container consul-client  Stopping
 Container grocery-items-management-api-gateway  Stopping
 Container grocery-items-management-api-gateway  Stopped
 Container grocery-items-management-api-gateway  Removing
 Container grocery-items-management-api-gateway  Removed
 Container grocery-items-management  Stopping
 Container consul-client  Stopped
 Container consul-client  Removing
 Container consul-client  Removed
 Container grocery-items-management  Stopped
 Container grocery-items-management  Removing
 Container grocery-items-management  Removed
 Container redis  Stopping
 Container zipkin  Stopping
 Container consul-server  Stopping
 Container redis  Stopped
 Container redis  Removing
 Container redis  Removed
 Container consul-server  Stopped
 Container consul-server  Removing
 Container consul-server  Removed
 Container zipkin  Stopped
 Container zipkin  Removing
 Container zipkin  Removed
 Network docker-compose_grocery-items-management-microservices  Removing
 Network docker-compose_grocery-items-management-microservicesmicroservices  Removed

```

# Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.