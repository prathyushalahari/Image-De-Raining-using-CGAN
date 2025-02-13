# Image-De-Raining-using-ID-CGAN
Collaborator - Chetan Nadigar

### **Abstract**  

Rain can significantly degrade image quality, affecting both human perception and the performance of computer vision systems in tasks like object detection and recognition. This project introduces a **Conditional Generative Adversarial Network (CGAN)-based model** for **single-image de-raining**, designed to remove rain streaks while preserving important details. The proposed method consists of two key components: **a generator** that translates rainy images into clear images and **a multi-scale discriminator** that ensures the generated images are indistinguishable from real, clean images.  

To enhance performance, the generator utilizes **dense connections and skip connections**, which improve gradient flow and ensure effective feature reuse. Additionally, a **refined loss function** is introduced, combining **adversarial loss (to improve realism), perceptual loss (to maintain texture and structure), and pixel-wise loss (to reduce errors)**. The model is trained on both **synthetic and real-world rainy datasets**, demonstrating superior results compared to traditional de-raining methods. Furthermore, experiments show that applying this model as a pre-processing step improves **object detection performance** in adverse weather conditions.
