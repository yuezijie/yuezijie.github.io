---
title: Awards
layout: page
hero_height: is-fullwidth
show_sidebar: false
---

<script src = "https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
- **2021.10 - 2023.09** Principal Investigator, **King's-NVIDIA Cambridge1 Grant** (£28K)
[<i id="award-02" style="color:red" aria-hidden="true">more</i>]

- **2021.01 - 2023.12** Investigator, **EU-H2020 Grant** (€2M)\\
[Restarting the Economy in Support of Environment, through Technology.](https://cordis.europa.eu/project/id/101017857)

- **2020.09 - 2021.09** Co-Principal Investigator, **King's Together Grant** (£18K)
[<i id="award-01" style="color:red" aria-hidden="true">more</i>]

- **2019.01 - 2020.12** Principal Investigator, **China National Natural Science Fund for Overseas Scholars** (¥180K)
[<i id="award-02" style="color:red" aria-hidden="true">more</i>]

<div id="detail-01" class="modal">
  <div class="modal-background"></div>
  <div class="modal-card">
    <header class="modal-card-head">
      <p class="modal-card-title">Award</p>
      <button class="delete" id="top-close-01" aria-label="close"></button>
    </header>
    <section class="modal-card-body">
      <div class="content">
        <h2>King’s Together Grant</h2>
        <p>This project is supported by King’s Together: Multi & Interdisciplinary Research Scheme which brings expertise from both Informatics and Geography to work on developing new machine learning approaches linked with (new) remote sensing data sources. 
           Our focus will be to develop algorithms to separate dammed reservoirs from the millions of other water bodies on Earth.  Pilot studies that we have carried out in the Volta and Limpopo basins indicate that dammed reservoirs tend to have a triangular or elongate triangular shape, whereas natural reservoirs tend to be round. 
           The goal of is to employ machine learning techniques, e.g. deep neural networks, to detect and recognize dammed reservoirs in remote sensing imagery. By identifying water bodies spectrally in earth observation imagery and then analysing their shape we hope to extend our database of large and medium sized dams to the many millions of small dams important for smallholder irrigation. 
        </p>
      </div>
    </section>
    <footer class="modal-card-foot">
        <button class="button" id="close-01">Close</button>
    </footer>
  </div>
</div>

<div id="detail-02" class="modal">
  <div class="modal-background"></div>
  <div class="modal-card">
    <header class="modal-card-head">
      <p class="modal-card-title">Award</p>
      <button class="delete" id="top-close-02" aria-label="close"></button>
    </header>
    <section class="modal-card-body">
      <div class="content">
        <h2>China National Natural Science Fund for Overseas Scholars</h2>
        <p>
        Using transfer learning to understand visual objects and their relationships
        Machine Perception tasks have flourished since the advent of deep learning techniques. Next key problem lies on visual scene understanding. To make sense of visual scenes, we need to rely on the visual object relationships inside, e.g. person riding a bike, book on the table. The challenge for this task is that 1) the training data is limited, on particular those unusual seen objects/object relationships; 2) visual relationships become complicated and diverse with an increase of object numbers. Recent works are mainly focused on detecting the normal relationships between any two objects.  
        This research shall employ the transfer learning methods to transfer available knowledge of visual relationships to new objects with unknown relationships. The significance of this research is not just to enhance the machine perception ability. The largest public dataset with full annotations (e.g. pixel classes/object bounding boxes) contains several million images, while billions of images on the Internet have no labels or only image-level labels. Research on transfer learning allows us to leverage a relatively small amount of expensively annotated images to detect new objects and their relationships in a much larger dataset without or with only cheap image-level labels. This is particularly important in the information era.
        </p>
      </div>
    </section>
    <footer class="modal-card-foot">
        <button class="button" id="close-02">Close</button>
    </footer>
  </div>
</div>

<script>
$("#award-01").click(function() {
  $("#detail-01").addClass("is-active");  
});
$("#top-close-01").click(function() {
   $("#detail-01").removeClass("is-active");
});
$("#close-01").click(function() {
   $("#detail-01").removeClass("is-active");
});
$("#award-02").click(function() {
  $("#detail-02").addClass("is-active");  
});
$("#top-close-02").click(function() {
   $("#detail-02").removeClass("is-active");
});
$("#close-02").click(function() {
   $("#detail-02").removeClass("is-active");
});
</script>
