<div class="slide-embed">
  <iframe
    src="https://uscedu-my.sharepoint.com/personal/mlgelman_usc_edu/_layouts/15/Doc.aspx?sourcedoc={31c106da-ec68-4a5f-956a-490d2b218f29}&action=embedview&wdAr=1.7777777777777777"
    frameborder="0"
    allowfullscreen
  ></iframe>
</div>

<style>
  /* center the block and let it span the full page width (cap optional) */
  .slide-embed {
    position: relative;
    width: 100%;
    max-width: 1200px;   /* optional: remove if you want truly edge-to-edge */
    margin: 0 auto;      /* centers the container */
  }

  /* responsive 16:9 ratio using the padding-top hack */
  .slide-embed::before {
    content: "";
    display: block;
    padding-top: 56.25%; /* 9/16 = 0.5625 */
  }

  /* make the iframe fill the container */
  .slide-embed iframe {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    border: 0;
  }

  /* optional: cap height on very tall screens */
  @media (min-height: 700px) {
    .slide-embed { max-height: 85vh; }
    .slide-embed iframe { height: 100%; }
  }
</style>
