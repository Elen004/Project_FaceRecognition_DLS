# Project_FaceRecognition_DLS

# Описание репазитория GitHub:

   1. В файле Part1_Stacked_Hourglass_Network описан принцип отбора датасета, представлен код реализации и обучения модели Stacked Hourglass Network для поиска ключевых точек лица, а также представлен    алгоритм для выравнивания изображений по найденным ключевым точкам (задание №1 Face Alignment).
   
   2. В файле Part_2_Модель_AC_loss_ArcFace выполнено обучение модели с использованием CrossEntropy loss, приведена реализациия ArcFace и выполнено обучение модели на ArcFace loss (задание №2 CE loss и ArcFace).

В папке Data хранятся следующие файлы:

   Файл selected_image_ids_2 (1): image_id отобранных в датасет изображений (txt)

   Файл selected_images_with_classes_2 (1):  image_id отобранных в датасет изображений, а также class_id (csv)
   


Все данные проекта и пайплайны (в виде ноутбуков Google colab) также хранятся в облачном хранилище на гугл диске. На гугл диске представлены более полные данные о проекте Face Recognition.

**Ссылка на гугл диск**: https://drive.google.com/drive/folders/1dyQClmi3j9a177Rqf8Mm4DXfBRYP6ONI?usp=sharing



# Описание проекта на гугл диске:

Все данные, пайплайны, а также сохранённые моделии хранятся в папке "Итоговый проект". 

   
   **I. Исходные файлы:**
     
Файлы list_landmarks_celeba.txt, list_bbox_celeba.txt, list_attr_celeba.csv представляют собой исходные файлы для полного датасета CelebA. Файл  ist_attr_celeba.csv был скачан с kaggle CelebA - Original Wild Images. Файлы  list_landmarks_celeba.txt, list_bbox_celeba.txt скачаны с официального сайта авторов оригинального датасета CelebA.
        
В паке "Датасет для второй части задания  (DLS_Проект_(3))" представлен файл identity_CelebA.txt, также взятый с сайта авторов полного датасета CelebA.

        
   **II. Изображения отобранные в датасет:**

В папке "Датасет_вариант 2" содержатся следующие файлы:

   selected_image_(2).zip - архив, содержащий 20 000 изображений, отобранных в датасет.

   selected_image_ids_2.txt (1): image_id отобранных в датасет изображений.

   selected_images_with_classes_2.csv (1):  image_id отобранных в датасет изображений, а также class_id.

   aligned_faces_full_dataset.zip - архив, содержащий выровненые и обрезаные изображения, полученные после выполнения задания №1 Face Alignment.


  **III. Ноутбуки с выполненными заданиями:**
      
В папке "Пайплайны" представлены ноутбуки Part1_Stacked_Hourglass_Network.ipnb, Part_2_Модель_AC_loss_ArcFace.ipnb (задание №1 Face Alignment, (задание №2 CE loss и ArcFace).


   **IV. Модели:**

В папке "models" представлены полученные модели:
         
stacked_hourglass_net.pth - модель для поиска ключевых точек;

best_model  CE loss (final_val_loss 0.73).pth - модель для распознавания лиц, обученная на CE loss

best_arcface_model (final_val_loss 0.74).pth - модель для распознавания лиц, обученная на ArcFace loss
      

            
            
        
