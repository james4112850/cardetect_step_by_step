

## 結構

  ![示意圖](./images/image.png)
<img width="331" height="112" alt="image" src="https://github.com/user-attachments/assets/d9726407-47d8-435d-9c55-b273e29a730f" />


- **step_a_preprocess1.py**: 圖像初步預處理。
  
  ![示意圖](./images/image1.png)
- **step_b_crop_car.py**: 從圖像中裁剪車輛。
  
  ![示意圖](./images/image2.png)
- **step_c_preprocess2.py**: 進一步圖像預處理。
    
  ![示意圖](./images/image3.png)
- **step_d_crop_plate.py**: 從車輛圖像中裁剪車牌。
    
  ![示意圖](./images/image4.png)
- **step_e_characters.py**: 分割車牌字元的步驟。
  
  ![示意圖](./images/image5.png)
- **utils.py**: 輔助功能和工具。


## 使用指南
1. 運行`step_a_preprocess1.py`進行初步預處理。
2. 使用`step_b_crop_car.py`裁剪車輛。
3. 執行`step_c_preprocess2.py`進一步預處理。
4. 使用`step_d_crop_plate.py`裁剪車牌。
5. 使用`step_e_characters.py`進行字元分割。


