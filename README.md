# LW-2-A — Plant Species Image Classification

## A. Project Overview
This project builds an image classification model to identify tropical and ornamental plant species using deep learning (CNN).

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

### 2. Hawaiian Sunshine Dracaena
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

### 6. Birdsnest Anthurium
<p align="center">
  <img src="https://github.com/user-attachments/assets/d4dfdab9-ebb0-46a7-8cde-811d2b396bf4" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Birdsnest Anthurium, Strap Leaf Anthurium |
| **Scientific Name** | *Anthurium jenmanii* |
| **Description** | A striking tropical with 2–3 ft glossy strap-like leaves rising in a bird's nest rosette, grown entirely for its dramatic architectural foliage. |

---

### 7. Snow Alternanthera
<p align="center">
  <img src="https://github.com/user-attachments/assets/f6b6e1a2-9d10-4cf3-b8ea-7cfa24ea0307" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Snow Alternanthera, Joseph's Coat, Calico Plant |
| **Scientific Name** | *Alternanthera ficoidea* 'Snow' |
| **Description** | A low-growing 6–12 inch foliage plant densely packed with white-and-green variegated leaves, ideal for borders and tropical bedding displays. |

---

### 8. Golden Spider Plant
<p align="center">
  <img src="https://github.com/user-attachments/assets/68d263f0-2053-46c8-96b3-56da2ea5b9cb" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Golden Spider Plant, Variegated Spider Plant |
| **Scientific Name** | *Chlorophytum comosum* 'Vittatum' |
| **Description** | A fountain-like houseplant with yellow-striped arching leaves that spawn cascading baby plantlets — adaptable, foolproof, and a proven air purifier. |

---

### 9. Wedelia (Singapore Daisy)
<p align="center">
  <img src="https://github.com/user-attachments/assets/9c3268ac-b851-4d9d-ae78-5c0fd6f2e05b" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Wedelia, Singapore Daisy, Trailing Daisy |
| **Scientific Name** | *Sphagneticola trilobata* |
| **Description** | A fast-creeping ground cover with year-round yellow daisy flowers — popular for erosion control but invasive across many tropical regions. |

---

### 10. Cast Iron Plant
<p align="center">
  <img src="https://github.com/user-attachments/assets/37db0d45-1639-4a1b-97e2-c542a0051c6e" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Cast Iron Plant, Bar Room Plant |
| **Scientific Name** | *Aspidistra elatior* |
| **Description** | A nearly indestructible foliage plant with tall glossy dark-green leaves, thriving in deep shade and neglect that would kill most houseplants. |

---

### 11. English Ivy
<p align="center">
  <img src="https://github.com/user-attachments/assets/51862dc2-653c-4db7-ac0e-97955fa3193c" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | English Ivy, Common Ivy |
| **Scientific Name** | *Hedera helix* |
| **Description** | An evergreen climbing vine with classic lobed leaves that covers walls or cascades indoors — valued yet invasive in many natural areas. |

---

### 12. Scarlet Sage
<p align="center">
  <img src="https://github.com/user-attachments/assets/d6299fb2-ba2a-4309-b13f-33c27ab7dfb6" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Scarlet Sage, Red Salvia |
| **Scientific Name** | *Salvia splendens* |
| **Description** | A vibrant flowering plant with brilliant red spikes blooming all summer, beloved for bold color in beds and its irresistible appeal to hummingbirds. |

---

### 13. Satsuki Azalea
<p align="center">
  <img src="https://github.com/user-attachments/assets/17593554-818f-41fd-b51f-750d75318767" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Satsuki Azalea, Indian Azalea |
| **Scientific Name** | *Rhododendron indicum* |
| **Description** | A compact evergreen shrub famous for spectacular spring blooms in pink, red, or white — a staple of Japanese gardens and a prized bonsai subject. |

---

### 14. African Marigold
<p align="center">
  <img src="https://github.com/user-attachments/assets/70b508b4-c1e3-40e8-a92f-cbc6d62357ce" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | African Marigold, Aztec Marigold, Mexican Marigold |
| **Scientific Name** | *Tagetes erecta* |
| **Description** | A prolific annual with large pompom blooms in bold yellow and orange — showy, long-blooming, and naturally effective at repelling garden pests. |

---

### 15. Madagascar Periwinkle
<p align="center">
  <img src="https://github.com/user-attachments/assets/28392642-5d68-4147-b96b-604fb22369f7" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Madagascar Periwinkle, Vinca, Rosy Periwinkle |
| **Scientific Name** | *Catharanthus roseus* |
| **Description** | A heat-loving, continuously blooming bedding plant containing medicinal alkaloids used in cancer treatment — reliable, low-maintenance, and vibrantly colorful. |

---

### 16. Wild White Petunia
<p align="center">
  <img src="https://github.com/user-attachments/assets/9876546e-2f98-4eb7-bf9c-4ddf5c973191" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Wild White Petunia, Large White Petunia |
| **Scientific Name** | *Petunia axillaris* |
| **Description** | A South American native with fragrant white trumpet blooms opening at dusk to attract moths — the key ancestor of all modern hybrid petunias. |

---

### 17. Floss Flower
<p align="center">
  <img src="https://github.com/user-attachments/assets/fe92d73d-1d5c-4392-a185-462d88c32805" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Floss Flower, Blue Mink, Blueweed |
| **Scientific Name** | *Ageratum houstonianum* |
| **Description** | A compact annual with fluffy powder-puff clusters in rare true blue, blooming spring through fall and attracting pollinators in borders and edging. |

---

### 18. Bunny Ears Cactus
<p align="center">
  <img src="https://github.com/user-attachments/assets/b3781aa8-73c4-4159-b127-dd30e79fea75" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Bunny Ears Cactus, Angel's Wings, Polka Dot Cactus |
| **Scientific Name** | *Opuntia microdasys* |
| **Description** | A Mexican cactus with flat oval pads dotted in golden glochids mimicking bunny ears — charming yet deceptively sharp, perfect for xeriscaping. |

---

### 19. Variegated Snake Plant
<p align="center">
  <img src="https://github.com/user-attachments/assets/040c9a92-f391-40b6-88e7-21d1f12e2b96" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Variegated Snake Plant, Mother-in-Law's Tongue |
| **Scientific Name** | *Dracaena trifasciata* 'Laurentii' |
| **Description** | A virtually indestructible upright succulent with yellow-edged sword leaves reaching 2–4 ft — one of the world's most forgiving and adaptable houseplants. |

---

### 20. Firecracker Plant
<p align="center">
  <img src="https://github.com/user-attachments/assets/31e3e8d1-eedb-4931-a932-e88b525fee24" width="350">
</p>

| Field | Details |
|---|---|
| **Common Name** | Firecracker Plant, Coral Plant, Fountain Plant |
| **Scientific Name** | *Russelia equisetiformis* |
| **Description** | A graceful cascading shrub with fountain-like rush stems and year-round tubular red blooms that are irresistible to hummingbirds and butterflies. |

---
