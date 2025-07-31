---
title: Graph Network Visualization
layout: page
permalink: /graph_network_words_works.html
---


<div class="mobile-friendly-iframe">
  <iframe src="{{ site.baseurl }}/assets/network_graph_words_work_layout.html" 
          allowfullscreen>
  </iframe>
</div>

<style>
.mobile-friendly-iframe {
  position: relative;
  width: 100%;
  height: 70vh; /* Use viewport height for better mobile experience */
  min-height: 400px;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.mobile-friendly-iframe iframe {
  width: 100%;
  height: 100%;
  border: none;
  transform-origin: 0 0;
}

/* Mobile optimizations */
@media (max-width: 768px) {
  .mobile-friendly-iframe {
    height: 80vh; /* Larger on mobile */
    min-height: 500px;
    margin: 10px -15px; /* Extend to screen edges */
    border-radius: 0;
  }
  
  .mobile-friendly-iframe iframe {
    /* Scale up the content for mobile */
    transform: scale(1.2);
    width: 83.33%; /* Compensate for scale */
    height: 83.33%;
  }
}

@media (max-width: 480px) {
  .mobile-friendly-iframe iframe {
    transform: scale(1.5); /* Even bigger on small phones */
    width: 66.67%;
    height: 66.67%;
  }
}
</style>

