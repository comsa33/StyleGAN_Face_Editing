# StyleGAN_Face_Editing
StyleGAN 전이학습을 통해서 face style 편집

## Face Embedding
  - VGG Feature Extractor(특징 추출기) : VGG 네트워크의 활성화 맵을 반환
  - Percetual Loss : VGG 활성화 맵상의 MSE loss, G(w)와 원본 이미지 사이에 있는 픽셀 상의 MSE 반환
  ![image-embedding](https://user-images.githubusercontent.com/61719257/159406023-917aae0b-8303-42c6-a757-34532dc04e42.png)
  ### [Image Embedding Results]
  ![ruo1-embedding](https://user-images.githubusercontent.com/61719257/159406093-8948303c-ce48-4090-8d79-325429d34f75.png) 
  ![pooh-embedding](https://user-images.githubusercontent.com/61719257/159406104-11a277f2-a1a7-43aa-bf5d-2b8a17e95b31.png)

## Face-Morphing
  ![image_morphing](https://user-images.githubusercontent.com/61719257/159406308-2be949f2-47b8-4fa2-bde6-c69ae86f8203.png)
  
## Crossover
  ![crossover](https://user-images.githubusercontent.com/61719257/159406423-f01c1a78-4e46-4ad9-94d0-c31ef7789ddb.png)
  ![ruo1](https://user-images.githubusercontent.com/61719257/159406474-319bf14e-a13d-49d1-a06b-4283d3c70d0e.png)
  ![joker](https://user-images.githubusercontent.com/61719257/159406487-84745ba6-7819-407f-9fa7-e83637b2d74d.png)
  ### [Result]
  ![face-crossover](https://user-images.githubusercontent.com/61719257/159406512-cb04b655-b194-4418-8180-a61354255f1c.png)
  
## Smile Face Style Transfer
  ![smile-face](https://user-images.githubusercontent.com/61719257/159406704-6a6260e4-71c4-4bf3-8c31-bd1265820d55.png)

## Straight Face Style Transfer
  ![straight-face](https://user-images.githubusercontent.com/61719257/159406711-03a3105f-8374-487c-809a-d52b8932cc50.png)

## Semantic Editing
  - 성별, 나이, 포즈, 웃음, 안경 착용여부 등 시멘틱 특징을 변경


  ![semantic-editing](https://user-images.githubusercontent.com/61719257/159406777-7071578e-b3a5-4bfe-a412-eb06daf6a451.png)
  
  ### [Gender Editing Result]
    
   ![semantic-gender](https://user-images.githubusercontent.com/61719257/159406894-5a56b2b9-80ee-4511-8132-3826ed35706f.png)
  
  ### [Age Editing Result]
  
   ![semantic-age](https://user-images.githubusercontent.com/61719257/159406972-c9f64ea2-726a-4e6c-9e94-d1df8d5e0fae.png)

  ### [Pose Editing Result]
  
   ![semantic-pose](https://user-images.githubusercontent.com/61719257/159406996-8f66705a-70ad-4483-907f-7ae04d54b9cd.png)

  ### [Glasses Editing Result]
  
   ![semantic-glasses](https://user-images.githubusercontent.com/61719257/159407032-351d506a-1bbc-4dbc-bc39-ef1201efaa04.png)

## Face Reconstruction
  ![face-reconstruction](https://user-images.githubusercontent.com/61719257/159407202-f3273d06-b5af-4d68-87d8-8e0a55fa5121.png)
  
  ### [Results]
  
  ![ruo-mask1](https://user-images.githubusercontent.com/61719257/159407279-bd45195a-b210-4d4b-95b1-e0a513601ef0.png)
  ![ruo-mask1-result](https://user-images.githubusercontent.com/61719257/159407285-5cc452e0-df49-4d3f-9a90-3b8a328e89eb.png)
  ---
  ![ruo-mask2](https://user-images.githubusercontent.com/61719257/159407393-f64bdce4-0060-459d-8635-f353d9a7313f.png)
  ![ruo-mask2-result](https://user-images.githubusercontent.com/61719257/159407385-a8324166-a8fb-44b1-b81d-8d8127c895ee.png)
  ---
  ![ruo-mask3](https://user-images.githubusercontent.com/61719257/159407418-453ee8cb-4d28-4f57-bf3b-4fd32d4b373a.png)
  ![ruo-mask3-result](https://user-images.githubusercontent.com/61719257/159407428-f46a51e8-4376-4097-918d-92ea7e40e484.png)
  

### reference
  - 이 레포지토리는 나동빈 님의 유튜브 영상과 깃허브를 참고했습니다.
  - https://www.youtube.com/watch?v=HXgfw3Z5zRo
  - https://github.com/ndb796/Deep-Learning-Paper-Review-and-Practice
