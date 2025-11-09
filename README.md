<style>
  .image-container {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    margin-top: 2rem;
  }

  .image-wrapper img {
    width: 100%;
  }

  @media (min-width: 768px) {
    .image-container {
      flex-direction: row;
    }
    .image-wrapper img {
      width: auto;
      height: 300px;
      object-fit: contain;
    }
  }
</style>

<div class="image-container">
  <div class="image-wrapper">
    <img 
      src="https://github-readme-stats.vercel.app/api?username=iHongRen&show_icons=true&theme=ambient_gradient" 
      alt="GitHub Stats" 
    >
  </div>
  <div class="image-wrapper">
    <img 
      src="https://github-readme-stats.vercel.app/api/top-langs/?username=iHongRen&layout=compact" 
      alt="Top Languages" 
    >
  </div>
</div>

