   
# Visual Tracking Evaluation results

## in Short Term Tracking


| <sub> Model </sub> | <sub> VOT16 (EAO/A/R)</sub>   | <sub> VOT18 (EAO/A/R) </sub>  | <sub> VOT19 (EAO/A/R) </sub>  | <sub> OTB2015 (AUC/Prec.)</sub> | <sub>VOT18-LT (F1) </sub> | <sub> Speed (fps)  </sub>  | <sub>ref. </sub> | <sub> dataset </sub> | 
|-------------------------------|-------------------|-------------------|-------------------|---------------------|---------------|----------------|------|------|
| <sub> siamrpn_alex_dwxcorr  </sub> | <sub> 0.393/0.618/0.238 </sub> | <sub> 0.352/0.576/0.290 </sub> | <sub> 0.260/0.573/0.547 </sub> | <sub> - </sub> | <sub> - </sub>      | <sub> 180  </sub>    | <sub> [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md)</sub> | <sub> 4<sub>1</sub>  </sub> |
| <sub> siamrpn_alex_dwxcorr_otb  </sub>    | <sub>-  </sub>   | <sub>- </sub>     | <sub>- </sub>    | <sub> 0.666/0.876 </sub>  | <sub> - </sub> | <sub> 180    </sub>  | <sub> [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md)</sub>|   <sub> 4<sub>1</sub>  </sub> |
| <sub> siamrpn_r50_l234_dwxcorr  </sub>    | <sub> 0.464/0.642/0.196 </sub> | <sub> 0.415/0.601/0.234 </sub> | <sub> 0.287/0.595/0.467 </sub> | <sub> -  </sub>     | <sub> - </sub> | <sub> 35    </sub>   | <sub> [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) </sub> | <sub> 4<sub>1</sub>  </sub> |
| <sub> siamrpn_r50_l234_dwxcorr_otb </sub>  | <sub> -   </sub>  | <sub> -    </sub> | <sub> -     </sub>      | <sub> 0.696/0.914   </sub>      | <sub> - </sub> | <sub> 35    </sub>   | <sub> [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) </sub> | <sub> 4<sub>1</sub>  </sub> |
| <sub> siamrpn_mobilev2_l234_dwxcorr </sub> | <sub> 0.455/0.624/0.214 </sub> | <sub> 0.410/0.586/0.229 </sub> | <sub> 0.292/0.580/0.446 </sub> | <sub> -  </sub>     | <sub> - </sub> | <sub> 75    </sub>   | <sub> [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md)<sub>  | <sub> 4<sub>1</sub>  </sub> | 
| <sub> siammask_r50_l3   </sub>      | <sub> 0.455/0.634/0.219 </sub> | <sub> 0.423/0.615/0.248 </sub> | <sub> 0.283/0.597/0.461 </sub> | <sub> -   </sub>    | <sub> - </sub> | <sub> 56   </sub>    | <sub> [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md)</sub> | <sub> 4<sub>1</sub>  </sub> |
| <sub> siamrpn_r50_l234_dwxcorr_lt </sub>  | <sub> -      </sub>     | <sub> -   </sub>  | <sub> -  </sub>   | <sub> -    </sub>   | <sub>0.629   | <sub>20  </sub>     | <sub> [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) </sub> | <sub> 4<sub>1</sub>  </sub> | 
| <sub> ATOM (CVPR2019)  </sub> | | <sub> 0.401/0.590/0.203 </sub> | |   |   | <sub> 43<sup>2</sup> </sub> | <sub> [link<sub>2</sub>](https://github.com/visionml/pytracking)  </sub>   | <sub> 3<sub>1</sub>  </sub> |
| <sub> DiMP (ICCV2019)  </sub> | | <sub> 0.441/0.597/0.152 </sub> | |   |   | <sub> 40    </sub>   | <sub> [link<sub>2</sub>](https://github.com/visionml/pytracking)  </sub> | <sub> 4<sub>2</sub>  </sub> |
| <sub> siamban (CVPR2020) </sub>    | | <sub> 0.452/0.597/0.178 </sub> |   |   |   | <sub> 45 </sub>    | <sub> [link<sub>3</sub>](https://github.com/hqucv/siamban)  </sub>   | <sub> 6<sub>1</sub>  </sub> |
| <sub> KYS (Arxiv2020)  </sub>  | | <sub> 0.462/0.609/0.143 </sub> | |   |   | <sub> 20<sup>3</sup> </sub> | <sub> [link<sub>2</sub>](https://github.com/visionml/pytracking)  </sub>    | <sub> 3<sub>2</sub>  </sub> |



### fps 
default = GTX 1080Ti <br>
fps<sup>2</sup> = GTX 1080 <br>
fps<sup>3</sup> = RTX 2080 <br>

### dataset
4<sub>1</sub> = COCO, ImageNet DET, ImageNet VID, and YouTube-BoundingBoxes Dataset <br>
3<sub>1</sub> = COCO, TrackingNet , LaSOT <br>
4<sub>2</sub> = COCO, TrackingNet , LaSOT , GOT10k <br>
6<sub>1</sub> = COCO, ImageNet DET, ImageNet VID, and YouTube-BoundingBoxes Dataset , LaSOT , GOT10k <br>

 

