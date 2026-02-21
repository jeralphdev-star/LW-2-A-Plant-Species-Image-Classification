<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LW-2-A — Plant Species Image Classification</title>
<link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,600;1,400&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: #ffffff;
    color: #1a1a1a;
    font-family: 'Inter', sans-serif;
    font-weight: 300;
  }

  /* ── HEADER ── */
  .header {
    border-bottom: 1px solid #e8e8e8;
    padding: 56px 64px 48px;
    max-width: 1200px;
    margin: 0 auto;
  }
  .header-tag {
    font-size: 11px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: #3a7d44;
    font-weight: 500;
    margin-bottom: 16px;
  }
  .header h1 {
    font-family: 'Lora', serif;
    font-size: clamp(1.8rem, 4vw, 3rem);
    font-weight: 600;
    color: #111;
    line-height: 1.2;
    margin-bottom: 12px;
  }
  .header p {
    color: #777;
    font-size: 0.95rem;
    max-width: 520px;
    line-height: 1.7;
  }
  .header-meta {
    display: flex;
    gap: 32px;
    margin-top: 32px;
    flex-wrap: wrap;
  }
  .meta-item { display: flex; flex-direction: column; gap: 2px; }
  .meta-val {
    font-family: 'Lora', serif;
    font-size: 1.4rem;
    color: #3a7d44;
    font-weight: 600;
  }
  .meta-label {
    font-size: 0.72rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: #aaa;
  }

  /* ── SECTION TITLE ── */
  .section-title {
    max-width: 1200px;
    margin: 0 auto;
    padding: 48px 64px 24px;
    display: flex;
    align-items: center;
    gap: 16px;
  }
  .section-title h2 {
    font-family: 'Lora', serif;
    font-size: 1.05rem;
    font-weight: 400;
    color: #999;
    white-space: nowrap;
  }
  .section-title hr {
    flex: 1;
    border: none;
    border-top: 1px solid #ebebeb;
  }

  /* ── GRID ── */
  .grid {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 64px 80px;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 24px;
  }

  /* ── CARD ── */
  .card {
    border: 1px solid #ebebeb;
    border-radius: 12px;
    overflow: hidden;
    background: #fff;
    transition: box-shadow 0.25s ease, transform 0.25s ease;
  }
  .card:hover {
    box-shadow: 0 8px 32px rgba(0,0,0,0.08);
    transform: translateY(-3px);
  }
  .card-img {
    width: 100%;
    aspect-ratio: 4 / 3;
    overflow: hidden;
    background: #f7f7f7;
  }
  .card-img img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    display: block;
    transition: transform 0.5s ease;
  }
  .card:hover .card-img img { transform: scale(1.05); }

  .card-body { padding: 18px 20px 22px; }
  .card-num {
    font-size: 10px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: #3a7d44;
    font-weight: 500;
    margin-bottom: 5px;
  }
  .card-common {
    font-family: 'Lora', serif;
    font-size: 1.05rem;
    color: #111;
    font-weight: 600;
    line-height: 1.3;
    margin-bottom: 3px;
  }
  .card-sci {
    font-family: 'Lora', serif;
    font-style: italic;
    font-size: 0.77rem;
    color: #bbb;
    margin-bottom: 12px;
  }
  .divider-line {
    height: 1px;
    background: #f0f0f0;
    margin-bottom: 12px;
  }
  .card-desc {
    font-size: 0.83rem;
    color: #666;
    line-height: 1.65;
  }

  /* ── FOOTER ── */
  footer {
    border-top: 1px solid #e8e8e8;
    text-align: center;
    padding: 32px 24px;
    font-size: 0.78rem;
    color: #ccc;
    letter-spacing: 0.06em;
  }
  footer strong { color: #3a7d44; }

  @media (max-width: 640px) {
    .header, .section-title { padding-left: 20px; padding-right: 20px; }
    .grid { padding: 0 20px 60px; }
  }
</style>
</head>
<body>

<header class="header">
  <div class="header-tag">LW-2-A &nbsp;·&nbsp; Image Classification Project</div>
  <h1>Plant Species<br>Image Classification</h1>
  <p>A curated dataset of tropical and ornamental plant species used to train and evaluate a deep learning image classification model.</p>
  <div class="header-meta">
    <div class="meta-item"><span class="meta-val">20</span><span class="meta-label">Species</span></div>
    <div class="meta-item"><span class="meta-val">CNN</span><span class="meta-label">Model Type</span></div>
    <div class="meta-item"><span class="meta-val">Tropical</span><span class="meta-label">Focus</span></div>
  </div>
</header>

<div class="section-title">
  <h2>B. Plant Species Catalog</h2>
  <hr>
</div>

<div class="grid">

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/7c333b0d-e5ad-4fae-8e87-a3a92b9af517" alt="Dwarf Snake Plant" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 01</div>
      <div class="card-common">Dwarf Snake Plant</div>
      <div class="card-sci">Sansevieria trifasciata 'Hahnii'</div>
      <div class="divider-line"></div>
      <p class="card-desc">A compact 6–8 inch rosette succulent — drought-tolerant, thrives in low light, and prized for air-purifying qualities with minimal care.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/2f720a3e-443a-43ed-a017-e740d8f4ec06" alt="Hawaiian Sunshine Dracaena" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 02</div>
      <div class="card-common">Hawaiian Sunshine Dracaena</div>
      <div class="card-sci">Dracaena fragrans 'Hawaiian Sunshine'</div>
      <div class="divider-line"></div>
      <p class="card-desc">A vibrant upright tropical reaching 3–4 ft indoors, with bold yellow-green striped leaves that tolerate low light and brighten any room.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/a20ac2a1-d0a4-42d1-bec4-9af6ee7a50cb" alt="Chinese Croton" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 03</div>
      <div class="card-common">Chinese Croton</div>
      <div class="card-sci">Codiaeum variegatum</div>
      <div class="divider-line"></div>
      <p class="card-desc">A bold tropical shrub with leathery, multi-colored leaves in yellow, orange, red, and purple — a dramatic ornamental for bright humid spaces.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/55de5579-4490-48e4-be43-d11db15ccb82" alt="Star of Bethlehem" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 04</div>
      <div class="card-common">Star of Bethlehem</div>
      <div class="card-sci">Hippobroma longiflora</div>
      <div class="divider-line"></div>
      <p class="card-desc">A delicate perennial with year-round white star-shaped blooms — beautiful yet highly toxic throughout and invasive across tropical regions.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/17b93055-4b50-4b3e-92cd-da8dac6dfa54" alt="Kaffir Lime Tree" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 05</div>
      <div class="card-common">Kaffir Lime Tree</div>
      <div class="card-sci">Citrus hystrix</div>
      <div class="divider-line"></div>
      <p class="card-desc">A tropical citrus tree with distinctive double-lobed aromatic leaves, essential to Southeast Asian cuisine for their intensely flavored zest.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/d4dfdab9-ebb0-46a7-8cde-811d2b396bf4" alt="Birdsnest Anthurium" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 06</div>
      <div class="card-common">Birdsnest Anthurium</div>
      <div class="card-sci">Anthurium jenmanii</div>
      <div class="divider-line"></div>
      <p class="card-desc">A striking tropical with 2–3 ft glossy strap-like leaves rising in a bird's nest rosette, grown entirely for its dramatic architectural foliage.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/f6b6e1a2-9d10-4cf3-b8ea-7cfa24ea0307" alt="Snow Alternanthera" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 07</div>
      <div class="card-common">Snow Alternanthera</div>
      <div class="card-sci">Alternanthera ficoidea 'Snow'</div>
      <div class="divider-line"></div>
      <p class="card-desc">A low-growing 6–12 inch foliage plant densely packed with white-and-green variegated leaves, ideal for borders and tropical bedding displays.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/68d263f0-2053-46c8-96b3-56da2ea5b9cb" alt="Golden Spider Plant" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 08</div>
      <div class="card-common">Golden Spider Plant</div>
      <div class="card-sci">Chlorophytum comosum 'Vittatum'</div>
      <div class="divider-line"></div>
      <p class="card-desc">A fountain-like houseplant with yellow-striped arching leaves that spawn cascading baby plantlets — adaptable, foolproof, and a proven air purifier.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/9c3268ac-b851-4d9d-ae78-5c0fd6f2e05b" alt="Wedelia" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 09</div>
      <div class="card-common">Wedelia (Singapore Daisy)</div>
      <div class="card-sci">Sphagneticola trilobata</div>
      <div class="divider-line"></div>
      <p class="card-desc">A fast-creeping ground cover with year-round yellow daisy flowers — popular for erosion control but invasive across many tropical regions.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/37db0d45-1639-4a1b-97e2-c542a0051c6e" alt="Cast Iron Plant" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 10</div>
      <div class="card-common">Cast Iron Plant</div>
      <div class="card-sci">Aspidistra elatior</div>
      <div class="divider-line"></div>
      <p class="card-desc">A nearly indestructible foliage plant with tall glossy dark-green leaves, thriving in deep shade and neglect that would kill most houseplants.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/51862dc2-653c-4db7-ac0e-97955fa3193c" alt="English Ivy" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 11</div>
      <div class="card-common">English Ivy</div>
      <div class="card-sci">Hedera helix</div>
      <div class="divider-line"></div>
      <p class="card-desc">An evergreen climbing vine with classic lobed leaves that covers walls or cascades indoors — valued yet invasive in many natural areas.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/d6299fb2-ba2a-4309-b13f-33c27ab7dfb6" alt="Scarlet Sage" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 12</div>
      <div class="card-common">Scarlet Sage</div>
      <div class="card-sci">Salvia splendens</div>
      <div class="divider-line"></div>
      <p class="card-desc">A vibrant flowering plant with brilliant red spikes blooming all summer, beloved for bold color in beds and its irresistible appeal to hummingbirds.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/17593554-818f-41fd-b51f-750d75318767" alt="Satsuki Azalea" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 13</div>
      <div class="card-common">Satsuki Azalea</div>
      <div class="card-sci">Rhododendron indicum</div>
      <div class="divider-line"></div>
      <p class="card-desc">A compact evergreen shrub famous for spectacular spring blooms in pink, red, or white — a staple of Japanese gardens and a prized bonsai subject.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/70b508b4-c1e3-40e8-a92f-cbc6d62357ce" alt="African Marigold" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 14</div>
      <div class="card-common">African Marigold</div>
      <div class="card-sci">Tagetes erecta</div>
      <div class="divider-line"></div>
      <p class="card-desc">A prolific annual with large pompom blooms in bold yellow and orange — showy, long-blooming, and naturally effective at repelling garden pests.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/28392642-5d68-4147-b96b-604fb22369f7" alt="Madagascar Periwinkle" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 15</div>
      <div class="card-common">Madagascar Periwinkle</div>
      <div class="card-sci">Catharanthus roseus</div>
      <div class="divider-line"></div>
      <p class="card-desc">A heat-loving, continuously blooming bedding plant containing medicinal alkaloids used in cancer treatment — reliable, low-maintenance, and vibrantly colorful.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/9876546e-2f98-4eb7-bf9c-4ddf5c973191" alt="Wild White Petunia" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 16</div>
      <div class="card-common">Wild White Petunia</div>
      <div class="card-sci">Petunia axillaris</div>
      <div class="divider-line"></div>
      <p class="card-desc">A South American native with fragrant white trumpet blooms opening at dusk to attract moths — the key ancestor of all modern hybrid petunias.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/fe92d73d-1d5c-4392-a185-462d88c32805" alt="Floss Flower" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 17</div>
      <div class="card-common">Floss Flower</div>
      <div class="card-sci">Ageratum houstonianum</div>
      <div class="divider-line"></div>
      <p class="card-desc">A compact annual with fluffy powder-puff clusters in rare true blue, blooming spring through fall and attracting pollinators in borders and edging.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/b3781aa8-73c4-4159-b127-dd30e79fea75" alt="Bunny Ears Cactus" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 18</div>
      <div class="card-common">Bunny Ears Cactus</div>
      <div class="card-sci">Opuntia microdasys</div>
      <div class="divider-line"></div>
      <p class="card-desc">A Mexican cactus with flat oval pads dotted in golden glochids mimicking bunny ears — charming yet deceptively sharp, perfect for xeriscaping.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/040c9a92-f391-40b6-88e7-21d1f12e2b96" alt="Variegated Snake Plant" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 19</div>
      <div class="card-common">Variegated Snake Plant</div>
      <div class="card-sci">Dracaena trifasciata 'Laurentii'</div>
      <div class="divider-line"></div>
      <p class="card-desc">A virtually indestructible upright succulent with yellow-edged sword leaves reaching 2–4 ft — one of the world's most forgiving and adaptable houseplants.</p>
    </div>
  </div>

  <div class="card">
    <div class="card-img"><img src="https://github.com/user-attachments/assets/31e3e8d1-eedb-4931-a932-e88b525fee24" alt="Firecracker Plant" loading="lazy"></div>
    <div class="card-body">
      <div class="card-num">Species 20</div>
      <div class="card-common">Firecracker Plant</div>
      <div class="card-sci">Russelia equisetiformis</div>
      <div class="divider-line"></div>
      <p class="card-desc">A graceful cascading shrub with fountain-like rush stems and year-round tubular red blooms that are irresistible to hummingbirds and butterflies.</p>
    </div>
  </div>

</div>

<footer>
  <strong>LW-2-A</strong> &nbsp;·&nbsp; Plant Species Image Classification &nbsp;·&nbsp; 20 Species Dataset
</footer>

</body>
</html>
