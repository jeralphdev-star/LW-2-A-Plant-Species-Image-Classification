# LW-2-A — Plant Species Image Classification

## A. Project Overview
The goal of this research is to create an image classification model that can identify 20 distinct species of decorative and tropical plants. We gathered more than 5,000 plant photos using Google Teachable Machine, and we trained a model to distinguish between different species using visual characteristics including bloom appearance, leaf shape, and color.

The objective is straightforward: to expedite and simplify plant identification. This device can identify the type of plant in a shot in a matter of seconds, eliminating the need to manually search for it. For students, gardeners, and anybody else interested in the plants around them, it's a useful illustration of how machine learning may be applied in daily life.

---

## B. Plant Species Catalog

### 1. Dwarf Snake Plant
<p align="center">
  <img src="https://github.com/user-attachments/assets/21cd50a5-1fb6-4e06-8db3-57a26726d401" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Dwarf Snake Plant, Bird's Nest Snake Plant |
| **Scientific Name** | *Sansevieria trifasciata* 'Hahnii' |
| **Description** | A compact 6–8 inch rosette succulent — drought-tolerant, thrives in low light, and prized for air-purifying qualities with minimal care. |

---

### 2. Dracaena 'Hawaiian Sunshine'
<p align="center">
  <img src="https://github.com/user-attachments/assets/bb5935ea-a8ec-4466-bb08-e4930026996d" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Hawaiian Sunshine Dracaena, Sunshine Dracaena |
| **Scientific Name** | *Dracaena fragrans* 'Hawaiian Sunshine' |
| **Description** | A vibrant upright tropical reaching 3–4 ft indoors, with bold yellow-green striped leaves that tolerate low light and brighten any room. |

---

### 3. Chinese Croton
<p align="center">
  <img src="https://github.com/user-attachments/assets/617e6119-158e-4a1f-abe4-7b633c98dd5a" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Chinese Croton, Garden Croton, Variegated Laurel |
| **Scientific Name** | *Codiaeum variegatum* |
| **Description** | A bold tropical shrub with leathery, multi-colored leaves in yellow, orange, red, and purple — a dramatic ornamental for bright humid spaces. |

---

### 4. Hippobroma Longiflora
<p align="center">
  <img src="https://github.com/user-attachments/assets/7d3b89be-eded-462c-aee1-6871141df778" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Star of Bethlehem, Madamfate, Horse Poison |
| **Scientific Name** | *Hippobroma longiflora* |
| **Description** | A delicate perennial with year-round white star-shaped blooms — beautiful yet highly toxic throughout and invasive across tropical regions. |

---

### 5. Kaffir Lime Tree
<p align="center">
  <img src="https://github.com/user-attachments/assets/b8f8eb94-5694-4654-8df8-58737605a8fa" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Kaffir Lime, Makrut Lime, Thai Lime |
| **Scientific Name** | *Citrus hystrix* |
| **Description** | A tropical citrus tree with distinctive double-lobed aromatic leaves, essential to Southeast Asian cuisine for their intensely flavored zest. |

---

### 6. Anthurium Jenmanii
<p align="center">
  <img src="https://github.com/user-attachments/assets/5aa68741-c7bf-4788-a3b2-9cdd08ff9422" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Birdsnest Anthurium, Strap Leaf Anthurium |
| **Scientific Name** | *Anthurium jenmanii* |
| **Description** | A striking tropical with 2–3 ft glossy strap-like leaves rising in a bird's nest rosette, grown entirely for its dramatic architectural foliage. |

---

### 7. Snow Alternanthera
<p align="center">
  <img src="https://github.com/user-attachments/assets/c28e66fa-36b2-47ad-bf64-fff7c325c305" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Snow Alternanthera, Joseph's Coat, Calico Plant |
| **Scientific Name** | *Alternanthera ficoidea* 'Snow' |
| **Description** | A low-growing 6–12 inch foliage plant densely packed with white-and-green variegated leaves, ideal for borders and tropical bedding displays. |

---

### 8. Golden Spider Plant
<p align="center">
  <img src="https://github.com/user-attachments/assets/aab6d252-8a76-43b4-bf0b-9f21a6314401" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Golden Spider Plant, Variegated Spider Plant |
| **Scientific Name** | *Chlorophytum comosum* 'Vittatum' |
| **Description** | A fountain-like houseplant with yellow-striped arching leaves that spawn cascading baby plantlets — adaptable, foolproof, and a proven air purifier. |

---

### 9. Wedelia (Singapore Daisy)
<p align="center">
  <img src="https://github.com/user-attachments/assets/c19d3fe7-4e22-469c-8761-f6126c21801c" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Wedelia, Singapore Daisy, Trailing Daisy |
| **Scientific Name** | *Sphagneticola trilobata* |
| **Description** | A fast-creeping ground cover with year-round yellow daisy flowers — popular for erosion control but invasive across many tropical regions. |

---

### 10. Cast Iron Plant
<p align="center">
  <img src="https://github.com/user-attachments/assets/5dd48edd-5b47-42c6-bc71-755ceeffdce0" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Cast Iron Plant, Bar Room Plant |
| **Scientific Name** | *Aspidistra elatior* |
| **Description** | A nearly indestructible foliage plant with tall glossy dark-green leaves, thriving in deep shade and neglect that would kill most houseplants. |

---

### 11. Hedera Helix
<p align="center">
  <img src="https://github.com/user-attachments/assets/54e96094-774b-4d41-9d49-7d6491cc25b5" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | English Ivy, Common Ivy |
| **Scientific Name** | *Hedera helix* |
| **Description** | An evergreen climbing vine with classic lobed leaves that covers walls or cascades indoors — valued yet invasive in many natural areas. |

---

### 12. Scarlet Sage
<p align="center">
  <img src="https://github.com/user-attachments/assets/d260b45b-900c-40e6-92d1-6cac6771c875" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Scarlet Sage, Red Salvia |
| **Scientific Name** | *Salvia splendens* |
| **Description** | A vibrant flowering plant with brilliant red spikes blooming all summer, beloved for bold color in beds and its irresistible appeal to hummingbirds. |

---

### 13. Satsuki Azalea
<p align="center">
  <img src="https://github.com/user-attachments/assets/fd1025ed-088a-4f2d-be01-b286f4828669" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Satsuki Azalea, Indian Azalea |
| **Scientific Name** | *Rhododendron indicum* |
| **Description** | A compact evergreen shrub famous for spectacular spring blooms in pink, red, or white — a staple of Japanese gardens and a prized bonsai subject. |

---

### 14. African Marigold
<p align="center">
  <img src="https://github.com/user-attachments/assets/326f0742-782d-4e4f-8c13-1caac92217ae" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | African Marigold, Aztec Marigold, Mexican Marigold |
| **Scientific Name** | *Tagetes erecta* |
| **Description** | A prolific annual with large pompom blooms in bold yellow and orange — showy, long-blooming, and naturally effective at repelling garden pests. |

---

### 15. Madagascar Periwinkle
<p align="center">
  <img src="https://github.com/user-attachments/assets/5cd1aa0c-6af6-4d3b-a82c-42da92503850" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Madagascar Periwinkle, Vinca, Rosy Periwinkle |
| **Scientific Name** | *Catharanthus roseus* |
| **Description** | A heat-loving, continuously blooming bedding plant containing medicinal alkaloids used in cancer treatment — reliable, low-maintenance, and vibrantly colorful. |

---

### 16. Wild White Petunia
<p align="center">
  <img src="https://github.com/user-attachments/assets/829198a8-add9-4de4-b390-119893626bfb" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Wild White Petunia, Large White Petunia |
| **Scientific Name** | *Petunia axillaris* |
| **Description** | A South American native with fragrant white trumpet blooms opening at dusk to attract moths — the key ancestor of all modern hybrid petunias. |

---

### 17. Floss Flower
<p align="center">
  <img src="https://github.com/user-attachments/assets/c900f8b6-c05e-4c76-82f4-e62c675c0e75" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Floss Flower, Blue Mink, Blueweed |
| **Scientific Name** | *Ageratum houstonianum* |
| **Description** | A compact annual with fluffy powder-puff clusters in rare true blue, blooming spring through fall and attracting pollinators in borders and edging. |

---

### 18. Bunny Ears Cactus
<p align="center">
  <img src="https://github.com/user-attachments/assets/5d97471a-c9c2-4455-a19c-cb4083d1181f" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Bunny Ears Cactus, Angel's Wings, Polka Dot Cactus |
| **Scientific Name** | *Opuntia microdasys* |
| **Description** | A Mexican cactus with flat oval pads dotted in golden glochids mimicking bunny ears — charming yet deceptively sharp, perfect for xeriscaping. |

---

### 19. Variegated Snake Plant
<p align="center">
  <img src="https://github.com/user-attachments/assets/466e7ff2-2a49-45ac-a530-b538c539a40d" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Variegated Snake Plant, Mother-in-Law's Tongue |
| **Scientific Name** | *Dracaena trifasciata* 'Laurentii' |
| **Description** | A virtually indestructible upright succulent with yellow-edged sword leaves reaching 2–4 ft — one of the world's most forgiving and adaptable houseplants. |

---

### 20. Firecracker Plant
<p align="center">
  <img src="https://github.com/user-attachments/assets/7930b038-0bc7-43dd-95c3-ca366ff606a3" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Firecracker Plant, Coral Plant, Fountain Plant |
| **Scientific Name** | *Russelia equisetiformis* |
| **Description** | A graceful cascading shrub with fountain-like rush stems and year-round tubular red blooms that are irresistible to hummingbirds and butterflies. |

---

## C. Model Training Details

The model was trained using Google Teachable Machine with the following configuration:

| Parameter | Value |
|---|---|
| **Epochs** | 100 |
| **Batch Size** | 16 |
| **Learning Rate** | 0.001 |
| **Number of Classes** | 20 |
| **Minimum Images per Class** | 250 |
| **Total Dataset Size** | 5,000+ images |

**Training Settings Screenshot:**

<p align="center">
  <img src="screenshots/training/training_settings.png" width="600">
</p>

**Why these values were chosen:**
- **Epochs (100):** Enough iterations to allow the model to learn patterns across all 20 classes without underfitting.
- **Batch Size (16):** A moderate batch size that balances training speed and model stability.
- **Learning Rate (0.001):** A standard learning rate that allows gradual and stable weight updates during training.

---

## D. Model Evaluation

### Confusion Matrix
<p align="center">
  <img src="screenshots/evaluation/Cunfusion_Matrix.png" width="700">
</p>

### Accuracy Per Class
<p align="center">
  <img src="screenshots/evaluation/Accuracy_Per_Class.png" width="700">
</p>
<p align="center">
  <img src="screenshots/evaluation/Accuracy_Per_Class_part_2.png" width="700">
</p>

### Overall Model Accuracy
<p align="center">
  <img src="screenshots/evaluation/Overall_Model_Accuracy.png" width="700">
</p>

### Accuracy Summary Table

| Class | Accuracy | # Samples |
|---|---|---|
| Dwarf Snake Plant | 1.00 | 67 |
| Dracaena 'Hawaiian Sunshine' | 0.98 | 55 |
| Chinese Croton | 0.99 | 151 |
| Hippobroma Longiflora | 1.00 | 71 |
| Kaffir Lime Tree | 0.98 | 99 |
| Anthurium Jenmanii | 1.00 | 61 |
| Snow Alternanthera | 0.91 | 54 |
| Golden Spider Plant | 1.00 | 167 |
| Wedelia (Singapore Daisy) | 0.99 | 87 |
| Cast Iron Plant | 0.98 | 90 |
| Hedera Helix | 0.96 | 72 |
| Scarlet Sage | 0.98 | 96 |
| Satsuki Azalea | 0.95 | 65 |
| African Marigold | 0.97 | 79 |
| Madagascar Periwinkle | 0.94 | 79 |
| Wild White Petunia | 0.95 | 88 |
| Floss Flower | 0.99 | 92 |
| Bunny Ears Cactus | 0.99 | 81 |
| Variegated Snake Plant | 0.99 | 112 |
| Firecracker Plant | 1.00 | 114 |

---

## E. Model Testing

Below are 10 testing screenshots from the Teachable Machine Preview section, each showing the input image, predicted plant class, and confidence score.

### Test 1 — Anthurium Jenmanii
<p align="center">
  <img src="screenshots/testing/Test_1_-_Anthurium_Jenmanii_model_testing_part1.png" width="600">
</p>
<p align="center">
  <img src="screenshots/testing/Test_1_-_Anthurium_Jenmanii_model_testing_part2.png" width="600">
</p>

**Result:** ✅ Anthurium Jenmanii — **100% Confidence**

---

### Test 2 — Chinese Croton
<p align="center">
  <img src="screenshots/testing/Test_2_-Chinese_Croton_model_testing_part_1.png" width="600">
</p>
<p align="center">
  <img src="screenshots/testing/Test_2_-_Chinese_Croton_model_testing_part_2.png" width="600">
</p>

**Result:** ✅ Chinese Croton — **100% Confidence**

---

### Test 3 — Dracaena 'Hawaiian Sunshine'
<p align="center">
  <img src="screenshots/testing/Test_3_-_Dracaena__Hawaiian_Sunshine_Model_Testing.png" width="600">
</p>

**Result:** ✅ Dracaena 'Hawaiian Sunshine' — **100% Confidence**

---

### Test 4 — Dwarf Snake Plant
<p align="center">
  <img src="screenshots/testing/Test_4_-_Dwarf_Snake_Plant_Model_Testing.png" width="600">
</p>

**Result:** ✅ Dwarf Snake Plant — **100% Confidence**

---

### Test 5 — Madagascar Periwinkle
<p align="center">
  <img src="screenshots/testing/Test_5_-_Madagascar_Periwinkle_model_testing_part_1.png" width="600">
</p>
<p align="center">
  <img src="screenshots/testing/Test_5_-_Madagascar_Periwinkle_model_testing_part_2.png" width="600">
</p>

**Result:** ✅ Madagascar Periwinkle — **82% Confidence**

---

### Test 6 — Satsuki Azalea
<p align="center">
  <img src="screenshots/testing/Test_6_-_Satsuki_Azalea_Model_Testing_part_1.png" width="600">

</p>
<p align="center">
  <img src="screenshots/testing/Test_6_-_Satsuki_Azalea_Model_Testing_part_2.png" width="600">
</p>

**Result:** ✅ Satsuki Azalea — **99% Confidence**

---

### Test 7 — Firecracker
<p align="center">
  <img src="screenshots/testing/Test_7_-_Firecracker_model_testing_part_1.png" width="600">
</p>
<p align="center">
  <img src="screenshots/testing/Test_7_-_Firecracker_model_testing_part_2.png" width="600">
</p>

**Result:** ✅ Scarlet Sage — **100% Confidence**

---

### Test 8 — Snow Alternanthera
<p align="center">
  <img src="screenshots/testing/Test_8_-_Snow_Alternanthera_model_testing_part1.png" width="600">
</p>
<p align="center">
  <img src="screenshots/testing/Test_8_-_Snow_Alternanthera_model_testing_part2.png" width="600">
</p>

**Result:** ✅ Snow Alternanthera — **100% Confidence**

---

### Test 9 — Variegated Snake Plant
<p align="center">
  <img src="screenshots/testing/Test_9_-_Variageted_Snake_Plant_part1.png" width="600">
</p>
<p align="center">
  <img src="screenshots/testing/Test_9_-_Variageted_Snake_Plant_part2.png" width="600">
</p>

**Result:** ✅ Variegated Snake Plant — **99% Confidence**

---

### Test 10 — Wedelia (Singapore Daisy)
<p align="center">
  <img src="screenshots/testing/Test_10_-_Wedelia_model_testing_part1.png" width="600">
</p>
<p align="center">
  <img src="screenshots/testing/Test_10_-_wedelia_model_testing_part2.png" width="600">
</p>

**Result:** ✅ Wedelia (Singapore Daisy) — **100% Confidence**

---

## F. Reflection Questions

### 1. How did the number of images per class affect your model's accuracy?
*(Write your answer here)*

### 2. Which plant species were most commonly misclassified and why?
*(Write your answer here)*

### 3. How did changing the epochs, batch size, or learning rate affect the training results?
*(Write your answer here)*

### 4. What challenges did you encounter during dataset collection and labeling?
*(Write your answer here)*

### 5. If you were to improve your model, what specific changes would you make and why?
*(Write your answer here)*
