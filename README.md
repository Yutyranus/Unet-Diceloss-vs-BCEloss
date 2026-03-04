# Unet-Diceloss-vs-BCEloss
So sánh độ hiệu quả của Dice loss và Binary Cross-Entropy - BCE loss trong việc segmentation cho bộ dữ liệu Oxford-IIIT Pet Dataset
1. Kết quả của mô hình khi sử dụng Dice loss

<img width="889" height="552" alt="image" src="https://github.com/user-attachments/assets/99676607-1785-4979-84ea-8f339a48a0c7" />
<img width="765" height="541" alt="image" src="https://github.com/user-attachments/assets/ab8ae108-47e7-476f-9699-78d034a10daa" />

2. Kết quả của mô hình khi sử dụng BCE loss

<img width="867" height="522" alt="image" src="https://github.com/user-attachments/assets/2976cf04-f535-4b9a-a7f6-c5a2342fe344" />
<img width="793" height="548" alt="image" src="https://github.com/user-attachments/assets/1316248b-7a2c-48fe-8e74-b1c24f77c175" />

3. Kết quả của mô hình khi sử dụng kết hợp Dice loss và BCE loss theo tỉ lệ 1:1 (Loss = Dice loss + BCE Loss)

<img width="873" height="536" alt="image" src="https://github.com/user-attachments/assets/fc23701c-5c8c-44bb-9c1e-0402738baeda" />
<img width="769" height="540" alt="image" src="https://github.com/user-attachments/assets/bd707fbc-2459-4f58-a21e-48516fd44c4a" />




